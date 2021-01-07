<template>
    <div class="w-full bg-no-repeat bg-cover py-6" :class="mobile ? 'block lg:hidden': 'hidden lg:block'" style="background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQ0MCIgaGVpZ2h0PSIxMDkwIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIj48ZGVmcz48cGF0aCBpZD0iYSIgZD0iTTAgMGgxNDQwdjEwOTBIMHoiLz48bGluZWFyR3JhZGllbnQgeDE9IjQ0LjI3JSIgeTE9Ijc1LjE2JSIgeDI9IjYxLjg3JSIgeTI9Ii0uMzElIiBpZD0iYiI+PHN0b3Agc3RvcC1jb2xvcj0iIzU2NDNFNSIgb2Zmc2V0PSIwJSIvPjxzdG9wIHN0b3AtY29sb3I9IiM1NjQzRTUiIHN0b3Atb3BhY2l0eT0iLjEiIG9mZnNldD0iMTAwJSIvPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IHgxPSI1Ni4yNCUiIHkxPSIyMy44NCUiIHgyPSIzOC40MSUiIHkyPSIxMDAuMzElIiBpZD0iZCI+PHN0b3Agc3RvcC1jb2xvcj0iIzM2NTA4MCIgc3RvcC1vcGFjaXR5PSIuMSIgb2Zmc2V0PSIwJSIvPjxzdG9wIHN0b3AtY29sb3I9IiMzNjUwODAiIG9mZnNldD0iMTAwJSIvPjwvbGluZWFyR3JhZGllbnQ+PC9kZWZzPjxnIGZpbGw9Im5vbmUiIGZpbGwtcnVsZT0iZXZlbm9kZCI+PG1hc2sgaWQ9ImMiIGZpbGw9IiNmZmYiPjx1c2UgeGxpbms6aHJlZj0iI2EiLz48L21hc2s+PHVzZSBmaWxsPSIjRjJGNUY3IiB4bGluazpocmVmPSIjYSIvPjxwYXRoIGZpbGw9InVybCgjYikiIGZpbGwtcnVsZT0ibm9uemVybyIgb3BhY2l0eT0iLjA0IiBtYXNrPSJ1cmwoI2MpIiBkPSJNMTE2OSAxNDQxLjU0bDY2OC4yMS0xNTc5LjhoMzA2LjY3bC02NjguMjIgMTU3OS44eiIvPjxwYXRoIGZpbGw9InVybCgjZCkiIGZpbGwtcnVsZT0ibm9uemVybyIgb3BhY2l0eT0iLjA0IiBtYXNrPSJ1cmwoI2MpIiBkPSJNLTEzMi4wMiAxMzU2LjQ5SC01NTdMMzY5LjAyLTgzMy41M0g3OTR6Ii8+PHBhdGggZmlsbD0idXJsKCNkKSIgZmlsbC1ydWxlPSJub256ZXJvIiBvcGFjaXR5PSIuMSIgbWFzaz0idXJsKCNjKSIgZD0iTS05MDcgMjU0MS42NkwxOS4wMiAzNTEuNjVINDQ0bC05MjYuMDIgMjE5MC4wMXoiLz48L2c+PC9zdmc+)">
        <div class="w-full lg:w-4/6 mx-auto px-4 lg:px-0 py-2 lg:py-6 lg:mt-0 flex lg:flex-row flex-col-reverse" >
            <div class="w-full lg:w-2/6">
                <div class="relative py-2 lg:py-6">
                    <span class="hidden lg:block absolute top-0 left-0 bg-positive mr-1 rounded-full px-2 text-xs leading-5 text-white">New</span>
                    <h3 class="font-bold text-xl lg:text-4xl text-center lg:text-left text-primary tracking-wider">
                        The TransferWise multi-currency account
                    </h3>
                    <p class="mt-4 text-secondary font-light text-sm lg:text-base leading-6 text-center lg:text-left">
                        Keep track of your transfers on the go with the TransferWise mobile app. Make new or repeat transfers - wherever you are - at the touch of a button.
                    </p>
                    <div class="w-full mt-6 hidden lg:block">
                        <button class="border border-accent text-accent rounded px-6 py-2 font-medium hover:text-white hover:bg-accent">Learn More</button>
                    </div>
                    <div class="flex flex-col lg:flex-row mt-6 space-x-0 lg:space-x-6 justify-center items-center">
                        <div class="w-1/2 space-y-2">
                            <img src="../assets/apple-store.svg" alt="apple store" class="w-full h-16">
                            <div class="hidden lg:block">
                                <svg class="tw-testimonial__rating" width="96" height="16"><defs><clipPath id="horizClip100-5ff5f8c5755dc107e0d925f2"><rect x="0" y="0" width="100%" height="16"></rect></clipPath></defs><g clip-path="url(#horizClip100-5ff5f8c5755dc107e0d925f2)"><path transform="translate(0, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(20, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(40, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(60, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(80, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path></g></svg>
                            </div>
                            <p class="hidden lg:block text-secondary font-light text-sm">4.8, 34.3K Ratings</p>
                        </div>
                        <div class="w-1/2 space-y-2">
                            <img src="../assets/android-store.svg" alt="apple store" class="w-full h-16">
                            <div class="hidden lg:block">
                                <svg class="tw-testimonial__rating" width="96" height="16"><defs><clipPath id="horizClip100-5ff5f8c5755dc107e0d925f2"><rect x="0" y="0" width="100%" height="16"></rect></clipPath></defs><g clip-path="url(#horizClip100-5ff5f8c5755dc107e0d925f2)"><path transform="translate(0, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(20, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(40, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(60, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path><path transform="translate(80, 0), scale(0.95)" fill="#ffb600" fill-rule="evenodd" d="M8.6 12.9l-5 2.6.9-5.6-4.1-4 5.7-.8L8.6 0l2.6 5.1 5.6.8-4.1 4 1 5.6z"></path></g></svg>
                            </div>
                            <p class="hidden lg:block text-secondary font-light text-sm">4.8, 34.3K Ratings</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="w-full lg:w-4/6 flex justify-center lg:justify-end mb-6">
                <div class="w-4/6 lg:w-3/6">
                    <img src="https://transferwise.com/staticrab/homepage/_next/static/images/borderless-phone-32fab951adaf29c41db9463191e38ccc.jpg" alt="apple store" class="w-full">
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    props:{
        mobile:{
            type: Boolean,
            required: true
        }
    }
}
</script>