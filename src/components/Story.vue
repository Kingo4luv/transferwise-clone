<template>
    <div class="w-full flex flex-col md:flex-row h-auto sm:h-auto md:lg:auto lg:h-story-height">
        <div class="w-full lg:w-1/2 z-0">
                <img :src="story.image" :alt="story.name" class="">
        </div>
        <div class="w-full lg:w-1/2 py-0 lg:py-16 z-10 border-box">
                <div class="h-auto bg-primary text-white px-4 lg:px-20 -ml-0 lg:-ml-24 flex flex-col justify-center py-6 lg:py-0 h-full lg:h-96 w-full">
                    <h3 class="font-medium lg:font-bold text-xl lg:text-2xl leading-8 tracking-wide">{{story.message}}</h3>
                    <p class="text-sm font-light mt-2">{{story.profile}}</p>
                    <div class="mt-4">
                    <button class="flex items-center border border-accent px-4 rounded py-2 leading-6 text-accent hover:text-white hover:bg-accent space-x-4">
                        <span>
                            <svg class="tw-play-icon text-current" fill="currentColor" width="30" height="30" xmlns="http://www.w3.org/2000/svg"><path d="M15 0c8.284 0 15 6.624 15 14.796v.408C30 23.376 23.284 30 15 30 6.716 30 0 23.376 0 15.204v-.408C0 6.624 6.716 0 15 0zm4.655 14.796l-7.241-5.612v11.224l7.241-5.612z" fill-rule="nonzero"></path></svg>
                        </span>
                        <span class="">See {{story.name}} story</span>
                    </button>
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
    }
}
</script>