<template>
<div>
    <div class="w-full flex flex-col md:flex-row h-auto sm:h-auto md:lg:auto lg:h-story-height relative">
        <div class="w-full h-full absolute inset-0">
            <div class="absolute right-80 bottom-3">
                 <svg class="tw-decorations-circle tw-customer-carousel-item__circle hidden-xs hidden-sm text-yellow-500" fill="currentColor" viewBox="0 0 160 160" xmlns="http://www.w3.org/2000/svg" width="160" height="160"><circle cx="80" cy="80" r="80"></circle></svg>
            </div>
        </div>
        <div class="w-full lg:w-1/2 z-0">
                <img :src="story.image" :alt="story.name" class="">
        </div>
        <div class="w-full lg:w-1/2 py-0 lg:py-16 z-10 border-box">
                <div class="bg-primary text-white px-4 lg:px-20 -ml-0 lg:-ml-24 flex flex-col justify-center py-6 lg:py-0 h-full lg:h-96 w-full">
                    <h3 class="font-medium lg:font-bold text-xl lg:text-2xl leading-8 tracking-wide">{{story.message}}</h3>
                    <p class="text-sm font-light mt-2">{{story.profile}}</p>
                    <div class="mt-4">
                    <button @click="$emit('openVideoModal', story.videoId )" class="flex items-center border border-accent px-4 rounded py-2 leading-6 text-accent hover:text-white hover:bg-accent space-x-4">
                        <span>
                            <svg class="tw-play-icon text-current transition-all delay-75" fill="currentColor" width="30" height="30" xmlns="http://www.w3.org/2000/svg"><path d="M15 0c8.284 0 15 6.624 15 14.796v.408C30 23.376 23.284 30 15 30 6.716 30 0 23.376 0 15.204v-.408C0 6.624 6.716 0 15 0zm4.655 14.796l-7.241-5.612v11.224l7.241-5.612z" fill-rule="nonzero"></path></svg>
                        </span>
                        <span class="">See {{story.name}} story</span>
                    </button>
                </div>
                </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    props:{
        story:{
            type: Object,
            required: true
        }
    },
    data(){
        return {
            
        }
    },
}
</script>