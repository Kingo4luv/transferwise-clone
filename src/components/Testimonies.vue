<template>
     <div class="w-full bg-no-repeat bg-cover py-8 lg:py-16 " style="background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQ0MCIgaGVpZ2h0PSIxMDkwIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIj48ZGVmcz48cGF0aCBpZD0iYSIgZD0iTTAgMGgxNDQwdjEwOTBIMHoiLz48bGluZWFyR3JhZGllbnQgeDE9IjQ0LjI3JSIgeTE9Ijc1LjE2JSIgeDI9IjYxLjg3JSIgeTI9Ii0uMzElIiBpZD0iYiI+PHN0b3Agc3RvcC1jb2xvcj0iIzU2NDNFNSIgb2Zmc2V0PSIwJSIvPjxzdG9wIHN0b3AtY29sb3I9IiM1NjQzRTUiIHN0b3Atb3BhY2l0eT0iLjEiIG9mZnNldD0iMTAwJSIvPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IHgxPSI1Ni4yNCUiIHkxPSIyMy44NCUiIHgyPSIzOC40MSUiIHkyPSIxMDAuMzElIiBpZD0iZCI+PHN0b3Agc3RvcC1jb2xvcj0iIzM2NTA4MCIgc3RvcC1vcGFjaXR5PSIuMSIgb2Zmc2V0PSIwJSIvPjxzdG9wIHN0b3AtY29sb3I9IiMzNjUwODAiIG9mZnNldD0iMTAwJSIvPjwvbGluZWFyR3JhZGllbnQ+PC9kZWZzPjxnIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+PG1hc2sgaWQ9ImMiIGZpbGw9IiNmZmYiPjx1c2UgeGxpbms6aHJlZj0iI2EiLz48L21hc2s+PHVzZSBmaWxsPSIjRjJGNUY3IiB4bGluazpocmVmPSIjYSIvPjxwYXRoIGZpbGw9InVybCgjYikiIGZpbGwtcnVsZT0ibm9uemVybyIgb3BhY2l0eT0iLjA0IiBtYXNrPSJ1cmwoI2MpIiBkPSJNMTE2OSAxNDQxLjU0bDY2OC4yMS0xNTc5LjhoMzA2LjY3bC02NjguMjIgMTU3OS44eiIvPjxwYXRoIGZpbGw9InVybCgjZCkiIGZpbGwtcnVsZT0ibm9uemVybyIgb3BhY2l0eT0iLjA0IiBtYXNrPSJ1cmwoI2MpIiBkPSJNLTEzMi4wMiAxMzU2LjQ5SC01NTdMMzY5LjAyLTgzMy41M0g3OTR6Ii8+PHBhdGggZmlsbD0idXJsKCNkKSIgZmlsbC1ydWxlPSJub256ZXJvIiBvcGFjaXR5PSIuMSIgbWFzaz0idXJsKCNjKSIgZD0iTS05MDcgMjU0MS42NkwxOS4wMiAzNTEuNjVINDQ0bC05MjYuMDIgMjE5MC4wMXoiLz48L2c+PC9zdmc+)">
        <div class="w-full lg:w-5/6 xl:w-4/6 mx-auto px-4 lg:px-0">
            <h2 class="font-bold tracking-wider text-xl lg:text-4xl text-primary text-center mb-4 lg:mb-10">
                For <span class="text-accent">where’s home? Long story</span> people.
            </h2>
            <carousel perPage=1 :autoplay="true" paginationActiveColor="#37517e">
                <slide v-for="story in stories" :key="story.name">
                    <Story :story="story" @openVideoModal="openModal"/>
                </slide>
            </carousel>
        </div>
        <div class="w-full lg:w-5/6 xl:w-4/6 mx-auto px-4 lg:px-0 mt-12">
           <div class="w-full lg:w-3/5 mx-auto">
                <h2 class="font-bold tracking-wider text-base lg:text-2xl text-primary text-center">
                    TrustPilot score 4.7 out of 5, from 105,507 reviews<span class="text-accent">.</span>
                </h2>
                <p class="text-sm text-secondary text-center px-2 lg:px-12 leading-6 mt-1">It’s your money. You can trust us to get it where it needs to be, but don’t take our word for it. Read our reviews at Trustpilot.com.</p>
           </div>
           <div class="mt-6 flex flex-col md:flex-row">
               <div class="w-full lg:w-1/3 p-2">
                <div class="w-full space-y-3 flex flex-col justify-center items-center text-center">
                    <span>
                        <svg class="tw-testimonial__rating" width="96" height="16"><defs><clipPath id="horizClip100-5ff5f8c5755dc107e0d925f2"><rect x="0" y="0" width="100%" height="16"></rect></clipPath></defs><g clip-path="url(#horizClip100-5ff5f8c5755dc107e0d925f2)"><path transform="translate(0, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(20, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(40, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(60, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(80, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path></g></svg>
                    </span>
                    <p class="px-2 lg:px-12 font-semibold text-primary text-sm lg:text-base">Easy to use, competitively priced and very quick to get transfers made.</p>
                    <div class="space-y-1">
                        <p class="font-semibold text-testimony text-xs lg:text-sm">Duncan</p>
                        <p class="font-semibold text-testimony text-xs lg:text-sm">Published 4 hours ago</p>
                    </div>
                </div>
               </div>
               <div class="w-full lg:w-1/3 p-2">
                <div class="w-full space-y-3 flex flex-col justify-center items-center text-center">
                    <span>
                        <svg class="tw-testimonial__rating" width="96" height="16"><defs><clipPath id="horizClip100-5ff5f8c5755dc107e0d925f2"><rect x="0" y="0" width="100%" height="16"></rect></clipPath></defs><g clip-path="url(#horizClip100-5ff5f8c5755dc107e0d925f2)"><path transform="translate(0, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(20, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(40, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(60, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(80, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path></g></svg>
                    </span>
                    <p class="px-2 lg:px-8 font-semibold text-primary text-sm lg:text-base">I’ve used a bunch of methods over the years to pay overseas contractors and Transferwise has been by far the…</p>
                    <div class="space-y-1">   
                        <p class="font-semibold text-testimony text-xs lg:text-sm">Rick D</p>
                        <p class="font-semibold text-testimony text-xs lg:text-sm">Published 4 hours ago</p>
                    </div>
                </div>
               </div>
               <div class="w-full lg:w-1/3 p-2">
                <div class="w-full space-y-3 flex flex-col justify-center items-center text-center">
                    <span>
                        <svg class="tw-testimonial__rating" width="96" height="16"><defs><clipPath id="horizClip100-5ff5f8c5755dc107e0d925f2"><rect x="0" y="0" width="100%" height="16"></rect></clipPath></defs><g clip-path="url(#horizClip100-5ff5f8c5755dc107e0d925f2)"><path transform="translate(0, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(20, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(40, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(60, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(80, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path></g></svg>
                    </span>
                    <p class="px-2 lg:px-8 font-semibold text-primary text-sm lg:text-base">I've been using TransferWise for over 2 years now and I am impressed with the savings compared to my bank…</p>
                    <div class="space-y-1">
                        <p class="font-semibold text-testimony text-xs lg:text-sm">Mme KASPAR C</p>
                        <p class="font-semibold text-testimony text-xs lg:text-sm">Published 4 hours ago</p>
                    </div>
                </div>
               </div>
           </div>
        </div>
        <div v-show="show" class="fixed top-0 left-0 w-full h-auto md:h-screen min-h-screen z-50 bg-overlay flex justify-center items-center px-2">
            <div class="h-52 md:h-4/5 w-full md:w-4/5 relative">
                <div class="absolute top-0 right-0 -mt-10">
                    <button @click="closeModal" class="focus:outline-none">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-6 h-6 text-white font-medium hover:text-accent" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd" />
                        </svg>
                    </button>
                </div>
                <youtube :video-id="videoId" :player-vars="playerVars" @playing="playing" class="w-full h-full"></youtube>
            </div>
        </div>
    </div>
</template>

<script>
import Story from './Story.vue'
import { Carousel, Slide } from 'vue-carousel';
export default {
    components:{
        Story,
        Carousel,
        Slide

    },
    data(){
        return{
            show: false,
            stories:[
                {
                    message: "I’ve probably saved two or three thousand dollars, and I’ll continue to save as I continue to use it.",
                    profile: "Sophie, Sydney, Australia",
                    name: "Sophie",
                    videoId: "OLkLdD7LynU",
                    image: "https://wise.com/static-assets/app/_next/static/images/sophie-ccda413f0d713f5d7330c0e6146fdc69.jpg",
                },
                {
                    message: "With TransferWise it's just so easy and effortless.",
                    profile: "Ejiro, Toronto, Canada",
                    name: "Ejiro",
                    videoId: "wt09PelQ_vI",
                    image: "https://wise.com/static-assets/app/_next/static/images/ejiro-275a884b244bfd2053ac4ec465b292ad.jpg"
                },
                {
                    message: "Using TransferWise for international payments just makes life really easy.",
                    profile: "Lucy and Yak, Brighton, UK",
                    name: "Lucy and Yak",
                    videoId: "WAoycsB_hn0",
                    image: "https://wise.com/static-assets/app/_next/static/images/lucyYak-14c19d066aee02f54230bfc017a2521f.jpg"
                },
            ],
            videoId: '',
            playerVars: {
                autoplay: 1
            }
        }
    },
    methods:{
        openModal(videoId){
            this.videoId = videoId,
            this.show = true
        },
        closeModal(){
            this.videoId = '',
            this.show = false
        }
    }
}
</script>

