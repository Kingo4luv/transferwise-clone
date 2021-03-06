<template>
   <div>
       <div class="input-container flex w-full rounded static lg:relative">
            <div class="bg-white rounded-l w-2/3 py-2 lg:py-3 px-3 flex flex-col">
                <span class="text-text-calculator font-light leading-5 text-sm">{{title}}</span>
                <input type="text" class="text-primary focus:outline-none text-xl tracking-wide" value="1,000">
            </div>
            <div @click="openFilter" v-click-outside="onClickOutside" tabindex="-1" 
                            @keyup.up.prevent="selectPrevOption"
                            @keyup.down.prevent="selectNextOption"
                class="bg-converter-button border border-transparent hover:border-gray-400 hover:bg-converter-border rounded-r w-1/3 cursor-pointer flex justify-between items-center px-2">
                <div class="flex items-center text-white space-x-2">
                    <country-flag :country="`${dataCurrency.icon}`" class="hidden lg:block" size='normal'/>
                    <span class="font-medium text-base lg:text-xl">{{dataCurrency.name}}</span>
                </div>
                <span>
                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="h-7  w-7  transition ease-in-out duration-150 text-accent" viewBox="0 0 24 24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/></svg>
                </span>
            </div>
            <transition
            enter-active-class="transform transition ease-in-out duration-500 "
            enter-class="translate-y-full lg:opacity-0 lg:translate-y-4 lg:translate-y-0 lg:scale-95"
            enter-to-class="translate-y-0 lg:opacity-100 lg:translate-y-0 lg:scale-100"
            leave-active-class="transform transition ease-in-out duration-500"
            leave-from-class="translate-y-0 lg:opacity-100 lg:translate-y-0 lg:scale-100"
            leave-to-class="translate-y-full lg:opacity-0 lg:translate-y-4 lg:translate-y-0 lg:scale-95"
            >
                <div v-show="showFilter" id="filterContainer"  class="w-full pl-0 lg:pl-6 fixed lg:absolute bottom-0 left-0 lg:top-0 lg:right-0 z-20">
                    <div id="filterInnerContainer" class="w-full bg-white rounded shadow-xl h-60 px-2 py-2 overflow-y-auto ">
                        <div class="w-full h-12 flex border-b py-2 items-center justify-between">
                            <span class="w-1/6 px-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-gray-500" viewBox="0 0 24 24" fill="currentColor"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"/></svg>
                            </span>
                            <input v-model="search" type="text" placeholder="Type a currency / country" class="w-full h-full text-gray-500 px-2 focus:outline-none font-light">
                        </div>
                        <div class="text-gray-600 text-sm mt-2">
                            <h2 id="filter" class="px-2 mb-2">All Currencies</h2>
                            <div id="container" class="w-full">
                                <div id="list" tabindex="0" class="w-full py-3 flex space-x-2 px-2 rounded tracking-wide cursor-pointer" :class="`${dataCurrency.icon === currency.icon ? 'bg-primary text-white': 'text-gray-600 hover:bg-gray-100'}`" v-for="(currency, index) in filteredCurrency" :key="index" @click="selectCurrency(currency)">
                                    <country-flag :country="`${currency.icon}`" size='normal' class="hidden lg:block"/>
                                    <span class="uppercase" :class="`${dataCurrency.icon === currency.icon ? 'text-white': 'text-gray-800'}`">{{currency.name}}</span>
                                    <span class="capitalize">{{currency.title}}</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </transition>
        </div>
   </div>
</template>
<script>
import CountryFlag from 'vue-country-flag'
import vClickOutside from 'v-click-outside'
export default {
    props:{
        country:{
            type:String,
            required: true
        },
        currency:{
            type: String,
            required: true
        },
        title:{
            type: String,
            required: true
        },
    },
    directives: {
      clickOutside: vClickOutside.directive
    },
    components: {
        CountryFlag
    },
    computed:{
        filteredCurrency(){
            return this.currencies.filter((currency) => {
                return currency.name.toLowerCase().match(this.search.toLowerCase());
            });
        },
        activeOptionIndex() {
            return this.filteredCurrency.findIndex(
                x => x.name === this.dataCurrency || x === this.dataCurrency
            );
        },
        prevOptionIndex() {
            const next = this.activeOptionIndex - 1;
            return next >= 0 ? next : this.filteredCurrency.length - 1;
        },
        nextOptionIndex() {
            const next = this.activeOptionIndex + 1;
            return next <= this.filteredCurrency.length - 1 ? next : 0;
        },
    },
    data(){
        return{
            showFilter: false,
            search:"",
            dataCurrency: {
                name:this.currency,
                icon: this.country
            },
            currencies: [
                {
                    name: "USD",
                    title: "United State Dollar",
                    icon: "us"
                },
                {
                    name: "GBP",
                    title: "British Pound",
                    icon: "gb"
                },
                {
                    name: "NGN",
                    title: "Nigerian Naira",
                    icon: "ng"
                },
                {
                    name: "INR",
                    title: "Indian Rupee",
                    icon: "in"
                },
                {
                    name: "GHS",
                    title: "Ghanaian Cedis",
                    icon: "gh"
                },
                {
                    name: "CNY",
                    title: "Chinese Yuan",
                    icon: "cn"
                }
            ]
        }
    },

    methods:{
        openFilter(){
            this.showFilter = true
        },
        closeFilter(){
            this.showFilter = false
        },
        onClickOutside (event) {
           if(event.target.id === 'filter' || event.target.type === 'text' || event.target.id === 'list' || event.target.id === 'container' || event.target.id === 'filterContainer' | event.target.id === 'filterInnerContainer' ){
               return;
           }
           return this.showFilter = false
        },
        selectCurrency(currency){
           this.dataCountry = currency.icon
           this.dataCurrency = currency.name
           this.closeFilter()
        },
         selectPrevOption() {
            this.dataCurrency = this.filteredCurrency[this.prevOptionIndex]
        },
        selectNextOption() {
            this.dataCurrency = this.filteredCurrency[this.nextOptionIndex]
        },
    },
}
</script>
