<template>
    <div class="w-full bg-white md:bg-fader-background py-10 lg:py-32 text-secondary md:text-white px-4 lg:px-0">
        <div class="w-full  lg:w-5/6 xl:w-4/6 mx-auto flex flex-col md:flex-row">
            <div class="w-full md:w-1/2 xl:w-2/5">
                <h3 class="font-bold text-lg lg:text-4xl text-center lg:text-left tracking-wider leading-8 px-4 lg:px-0 text-primary md:text-white">
                    We’re building money without borders<span class="text-accent">.</span>
                </h3>
                <p class="mt-5 font-light tracking-wide text-sm text-center lg:text-left">
                    The world’s banking systems weren’t designed for people without borders. That’s why we’re building a new one.
                </p>
                <div class="flex flex-col-reverse md:flex-col text-primary md:text-white">
                    <ol class="text-sm font-semibold mt-6 space-y-2">
                        <li class="tracking-wider"><span class="text-accent mr-2">1.</span>Be radically transparent</li>
                        <li class="tracking-wider"><span class="text-accent mr-2">2.</span>Charge as little as possible</li>
                        <li class="tracking-wider"><span class="text-accent mr-2">3.</span>Make premium the new normal</li>
                    </ol>
                    <div class="md:w-48 w-full">
                        <button class="mt-6 lg:mt-10 w-full px-6 py-3 rounded text-accent hover:text-white bg-transparent hover:bg-accent border border-accent">Find out more</button>
                    </div>
                </div>
            </div>
            <div class="w-full md:w-1/2 lg:w-3/5 flex items-center justify-center sm:mt-10 md:mt-0 mt-16 ">
                <div class="w-full sm:w-3/5 xl:w-2/5 h-80 lg:h-auto">
                    <transition
                enter-active-class="transform transition ease-in-out duration-700"
                enter-class="opacity-0 translate-y-4 scale-0"
                enter-to-class="opacity-100 translate-y-0 scale-100"
                leave-active-class="transform transition ease-in-out duration-700"
                leave-from-class="opacity-100 translate-y-0 scale-100"
                leave-to-class="opacity-0 translate-y-4 scale-0"
                >
                    <img v-show="show" :src="current.src" class="w-full h-full sm:h-60 lg:h-full " alt="">
                </transition>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    mounted(){
        this.getCurrent();
    },
    data(){
        return{
            show: false,
            current: null,
            currentIndex: 0,
            images: [
                {
                    src: "https://transferwise.com/staticrab/homepage/_next/static/images/person_4-fa5dd84167ab3c4d9fed376d6f49a587.jpg"
                },
                {
                    src: "https://transferwise.com/staticrab/homepage/_next/static/images/person_5-be82fc2ce9ea69c4c325526748211823.jpg"
                },
                {
                    src: "https://transferwise.com/staticrab/homepage/_next/static/images/person_7-54f69ec095ce4601e2d963c092b1dfd6.jpg"
                }
            ]
        }
    },

    methods:{
        getCurrent(){
            if(this.current === null){
                this.current = this.images[0];
                setTimeout(() => {
                    this.show = true;
                    this.hideCurrent();
                }, 2000);
                
            }else{
                if(this.currentIndex === this.images.length - 1){
                    setTimeout(() => {
                        this.show = true;
                        this.current = this.images[0];
                        this.currentIndex = 0
                        this.hideCurrent()
                    }, 2000);
                }else{
                    setTimeout(() => {
                        this.show = true;
                        this.current = this.images[this.currentIndex + 1];
                        this.currentIndex = this.currentIndex + 1
                        this.hideCurrent()
                    }, 2000);
                }
            }
        },
        hideCurrent(){
            setTimeout(() => {
                    this.show = false;
                    this.getCurrent();
            }, 2000);
        }
    }
}
</script>