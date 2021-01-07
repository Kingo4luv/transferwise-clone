<template>
   <div>
       <div class="input-container flex w-full rounded static lg:relative">
            <div class="bg-white rounded-l w-2/3 py-2 lg:py-3 px-3 flex flex-col">
                <span class="text-text-calculator font-light leading-5 text-sm">{{title}}</span>
                <input type="text" class="text-primary focus:outline-none text-xl tracking-wide" value="1,000">
            </div>
            <div @click="openFilter" v-click-outside="onClickOutside" class="bg-converter-button border border-transparent hover:border-gray-400 hover:bg-converter-border rounded-r w-1/3 cursor-pointer flex justify-between items-center px-2">
                <div class="flex items-center text-white space-x-2">
                    <country-flag :country="`${dataCountry}`" class="hidden lg:block" size='normal'/>
                    <span class="font-medium text-base lg:text-xl">{{dataCurrency}}</span>
                </div>
                <span>
                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="h-7  w-7  transition ease-in-out duration-150 text-accent" viewBox="0 0 24 24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/></svg>
                </span>
            </div>
            <transition
            enter-active-class="transform transition ease-in-out duration-500 "
            enter-class="opacity-0 translate-y-4 translate-y-0 scale-95"
            enter-to-class="opacity-100 translate-y-0 scale-100"
            leave-active-class="transform transition ease-in-out duration-500"
            leave-from-class="opacity-100 translate-y-0 scale-100"
            leave-to-class="opacity-0 translate-y-4 sm:translate-y-0 scale-95"
            >
                <div v-show="showFilter"  class="w-full pl-6 absolute top-0 right-0 hidden lg:block z-10">
                    <div class="w-full bg-white rounded shadow-xl h-60 px-2 py-2 overflow-y-auto ">
                        <div class="w-full h-12 flex border-b py-2 items-center justify-between">
                            <span class="w-1/6 px-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-gray-500" viewBox="0 0 24 24" fill="currentColor"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"/></svg>
                            </span>
                            <input type="text" placeholder="Type a currency / country" class="w-full h-full text-gray-500 px-2 focus:outline-none font-light">
                        </div>
                        <div class="text-gray-600 text-sm mt-2">
                            <h2 class="px-2 mb-2">All Currencies</h2>
                            <div class="w-full">
                                <div class="w-full py-3 flex space-x-2 px-2 rounded tracking-wide cursor-pointer" :class="`${dataCountry === currency.icon ? 'bg-primary text-white': 'text-gray-600 hover:bg-gray-100'}`" v-for="(currency, index) in currencies" :key="index" @click="selectCurrency(currency)">
                                    <country-flag :country="`${currency.icon}`" size='normal' class="hidden lg:block"/>
                                    <span class="uppercase" :class="`${dataCountry === currency.icon ? 'text-white': 'text-gray-800'}`">{{currency.name}}</span>
                                    <span class="capitalize">{{currency.title}}</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </transition>
            <transition
            enter-active-class="transform transition ease-in-out duration-500 sm:duration-700"
            enter-class="translate-y-full"
            enter-to-class="translate-y-0"
            leave-active-class="transform transition ease-in-out duration-500 sm:duration-700"
            leave-from-class="translate-y-0"
            leave-to-class="translate-y-full"
            >
                <div v-show="showFilter"  class="w-full fixed bottom-0 left-0 block lg:hidden z-20">
                    <div class="w-full bg-white rounded shadow-xl h-60 px-2 py-2 overflow-y-auto ">
                        <div class="w-full h-12 flex border-b py-2 items-center justify-between">
                            <span class="w-1/6 px-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 text-gray-500" viewBox="0 0 24 24" fill="currentColor"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z"/></svg>
                            </span>
                            <input type="text" id="input" placeholder="Type a currency / country" class="w-full h-full text-gray-500 px-2 focus:outline-none font-light">
                        </div>
                        <div class="text-gray-600 text-sm mt-2">
                            <h2 class="px-2 mb-2">All Currencies</h2>
                            <div class="w-full">
                                <div class="w-full py-3 flex space-x-2 px-2 rounded tracking-wide cursor-pointer" :class="`${dataCountry === currency.icon ? 'bg-primary text-white': 'text-gray-600 hover:bg-gray-100'}`" v-for="(currency, index) in currencies" :key="index" @click="selectCurrency(currency)">
                                    <country-flag :country="`${currency.icon}`" size='normal'/>
                                    <span class="uppercase" :class="`${dataCountry === currency.icon ? 'text-white': 'text-gray-800'}`">{{currency.name}}</span>
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
    data(){
        return{
            showFilter: false,
            dataCountry: this.country,
            dataCurrency: this.currency,
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
        onClickOutside (event) {
           if(event.target.id !== 'input'){
               return this.showFilter = false
           }
        },
        selectCurrency(currency){
           this.dataCountry = currency.icon
           this.dataCurrency = currency.name
        }
    },
}
</script>
