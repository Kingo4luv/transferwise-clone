<template>
    <div class="w-full bg-white px-4 rounded">
        <div class="header text-primary text-sm font-medium mb-3 py-5 flex justify-between items-center" @click="toggleShow">
            <span>{{feedback.title}}</span>
            <button  class="cursor-pointer focus:outline-none">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6 text-accent" v-html="icon"></svg>
            </button>
        </div>
        <div v-show="show" class="pb-4">
            <p class="text-secondary font-light text-sm leading-5 tracking-wide">{{feedback.message}}</p>
        </div>
    </div>
</template>

<script>
export default {
    props:{
        feedback:{
            type: Object,
            required: true
        }
    },
    computed:{
        icon(){
            if(this.show){
                return  `<path class="heroicon-ui" d="M8.7 14.7a1 1 0 0 1-1.4-1.4l4-4a1 1 0 0 1 1.4 0l4 4a1 1 0 0 1-1.4 1.4L12 11.42l-3.3 3.3z"/>`;
            }
            return `<path class="heroicon-ui" d="M15.3 9.3a1 1 0 0 1 1.4 1.4l-4 4a1 1 0 0 1-1.4 0l-4-4a1 1 0 0 1 1.4-1.4l3.3 3.29 3.3-3.3z"/>`;
        }
    },
    data(){
        return{
            show: false
        }
    },
    methods:{
        toggleShow(){
            this.show = !this.show;
        }
    }
}
</script>