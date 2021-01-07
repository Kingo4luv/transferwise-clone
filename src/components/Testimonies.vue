<template>
     <div class="w-full bg-no-repeat bg-cover py-8 lg:py-16 " style="background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQ0MCIgaGVpZ2h0PSI3MDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPgogIDxkZWZzPgogICAgPHBhdGggaWQ9ImEiIGQ9Ik0wIDBoMTQ0MHY2OThMMCA3MDB6Ii8+CiAgICA8bGluZWFyR3JhZGllbnQgeDE9IjQ0LjMlIiB5MT0iNzUuMiUiIHgyPSI2MS45JSIgeTI9Ii0uMyUiIGlkPSJiIj4KICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzU2NDNFNSIgb2Zmc2V0PSIwJSIvPgogICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjNTY0M0U1IiBzdG9wLW9wYWNpdHk9Ii4xIiBvZmZzZXQ9IjEwMCUiLz4KICAgIDwvbGluZWFyR3JhZGllbnQ+CiAgICA8bGluZWFyR3JhZGllbnQgeDE9IjU2LjIlIiB5MT0iMjMuOCUiIHgyPSIzOC40JSIgeTI9IjEwMC4zJSIgaWQ9ImQiPgogICAgICA8c3RvcCBzdG9wLWNvbG9yPSIjMzY1MDgwIiBzdG9wLW9wYWNpdHk9Ii4xIiBvZmZzZXQ9IjAlIi8+CiAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMzNjUwODAiIG9mZnNldD0iMTAwJSIvPgogICAgPC9saW5lYXJHcmFkaWVudD4KICAgIDxsaW5lYXJHcmFkaWVudCB4MT0iNTYuMiUiIHkxPSIyMy44JSIgeDI9IjM4LjQlIiB5Mj0iMTAwLjMlIiBpZD0iZSI+CiAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiMzNjUwODAiIHN0b3Atb3BhY2l0eT0iLjEiIG9mZnNldD0iMCUiLz4KICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iIzM2NTA4MCIgb2Zmc2V0PSIxMDAlIi8+CiAgICA8L2xpbmVhckdyYWRpZW50PgogIDwvZGVmcz4KICA8ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPgogICAgPG1hc2sgaWQ9ImMiIGZpbGw9IiNmZmYiPgogICAgICA8dXNlIHhsaW5rOmhyZWY9IiNhIi8+CiAgICA8L21hc2s+CiAgICA8dXNlIGZpbGw9IiNGRkYiIHhsaW5rOmhyZWY9IiNhIi8+CiAgICA8cGF0aCBmaWxsPSJ1cmwoI2QpIiBmaWxsLXJ1bGU9Im5vbnplcm8iIG9wYWNpdHk9Ii4yIiBtYXNrPSJ1cmwoI2MpIiBkPSJNMzk3LjUgMjk1MUgtMTgwTDEwNzguNS0yN0gxNjU2eiIvPgogICAgPHBhdGggZmlsbD0idXJsKCNlKSIgZmlsbC1ydWxlPSJub256ZXJvIiBvcGFjaXR5PSIuMSIgbWFzaz0idXJsKCNjKSIgZD0iTS05MDcgMjUyMy43bDkyNi0yMTkyaDQyNWwtOTI2IDIxOTJ6Ii8+CiAgPC9nPgo8L3N2Zz4=)">
        <div class="w-full lg:w-4/6 mx-auto px-4 lg:px-0">
            <h2 class="font-bold tracking-wider text-xl lg:text-4xl text-primary text-center mb-4 lg:mb-10">
                For <span class="text-accent">where’s home? Long story</span> people.
            </h2>
            <carousel perPage=1 :autoplay="true" paginationActiveColor="#37517e">
                <slide v-for="story in stories" :key="story.name">
                    <Story :story="story"/>
                </slide>
            </carousel>
        </div>
        <div class="w-full lg:w-4/6 mx-auto px-4 lg:px-0 mt-12">
           <div class="w-full lg:w-3/5 mx-auto">
                <h2 class="font-bold tracking-wider text-base lg:text-2xl text-primary text-center">
                    TrustPilot score 4.7 out of 5, from 105,507 reviews<span class="text-accent">.</span>
                </h2>
                <p class="text-sm font-light text-secondary text-center px-2 lg:px-12 leading-6 mt-1">It’s your money. You can trust us to get it where it needs to be, but don’t take our word for it. Read our reviews at Trustpilot.com.</p>
           </div>
           <div class="mt-6 flex flex-col lg:flex-row">
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
            stories:[
                {
                    message: "I’ve probably saved two or three thousand dollars, and I’ll continue to save as I continue to use it.",
                    profile: "Sophie, Sydney, Australia",
                    name: "Sophie",
                    image: "https://transferwise.com/staticrab/homepage/_next/static/images/sophie-ccda413f0d713f5d7330c0e6146fdc69.jpg",
                },
                {
                    message: "With TransferWise it's just so easy and effortless.",
                    profile: "Ejiro, Toronto, Canada",
                    name: "Ejiro",
                    image: "https://transferwise.com/staticrab/homepage/_next/static/images/ejiro-275a884b244bfd2053ac4ec465b292ad.jpg"
                },
                {
                    message: "Using TransferWise for international payments just makes life really easy.",
                    profile: "Lucy and Yak, Brighton, UK",
                    name: "Lucy and Yak",
                    image: "https://transferwise.com/staticrab/homepage/_next/static/images/lucyYak-14c19d066aee02f54230bfc017a2521f.jpg"
                },
            ]
        }
    }
}
</script>

