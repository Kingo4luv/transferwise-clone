<template>
    <div class="w-full bg-white md:bg-fader-background  text-secondary md:text-white px-4 lg:px-0 h-auto overflow-hidden">
        <div class="w-full h-full  lg:w-5/6 xl:w-4/6 mx-auto flex flex-col md:flex-row">
            <div class="w-full md:w-1/2  py-10 lg:py-32">
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
            <div class="w-full md:w-1/2 flex h-80 lg:h-96 mb-10 md:mb-0 md:h-auto relative px-2 md:px-16 image-container overflow-hidden">
                <div class="w-1/4 relative h-full box-border block">
                    <img class="image-1 column-1 opacity-40 absolute transform -translate-y-28 " src="https://transferwise.com/staticrab/homepage/_next/static/images/person_22-bc50bc1a346cba30fb6e407ac67a0667.jpg" alt="">
                    <img class="image-2 column-1 opacity-40 absolute transform -translate-y-28" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_9-c26aad8759c5efce2161ddd522bc2a01.jpg" alt="">
                    <img class="image-3 column-1 opacity-40 absolute hidden md:block transform -translate-y-28" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_10-b1205d9bad12cb4a21f8e282e2bb2631.jpg" alt="">
                </div>
                 <div class="w-1/4 relative h-full box-border block">
                    <img class="image-1 column-2 opacity-40 absolute transform -translate-y-28 " src="https://transferwise.com/staticrab/homepage/_next/static/images/person_13-c2122cf06d2eb705e98d0d3d19ecf80f.jpg" alt="">
                    <img class="image-2 column-2 opacity-40 absolute transform -translate-y-28" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_14-846e74d3a2d100fa1cf372baaf952ab3.jpg" alt="">
                    <img class="image-3 column-2 opacity-40 absolute hidden md:block transform -translate-y-32" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_12-1baedd7f4cd7c73b7f3d9bbdd4590afc.jpg" alt="">
                </div>
                 <div class="w-1/4 col-3 relative h-full box-border block">
                    <img class="image-1 column-3 opacity-40 absolute transform -translate-y-28 " src="https://transferwise.com/staticrab/homepage/_next/static/images/person_5-be82fc2ce9ea69c4c325526748211823.jpg" alt="">
                    <img class="image-2 column-3 opacity-40 absolute transform -translate-y-28" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_8-3579374f699f5fe66c9f949395df90f7.jpg" alt="">
                    <img class="image-3 column-3 opacity-40 absolute hidden md:block transform -translate-y-32" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_1-c67d50b951a7e1a3d5d72237ade0cf14.jpg" alt="">
                </div>
                 <div class="w-1/4 relative h-full box-border block">
                    <img class="image-1 column-2 opacity-40 absolute transform -translate-y-28 " src="https://transferwise.com/staticrab/homepage/_next/static/images/person_19-37fcb5779b86bb5585a139090d8db90d.jpg" alt="">
                    <img class="image-2 column-2 opacity-40 absolute transform -translate-y-28" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_15-2c2e24621c42972e306dfe244227fcd9.jpg" alt="">
                    <img class="image-3 column-2 opacity-40 absolute hidden md:block transform -translate-y-28" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_16-f221b24fc37acca2e1edf3ec5bb4dd99.jpg" alt="">
                </div>
                 <div class="w-1/4 relative h-full box-border block">
                    <img class="image-1 column-1 opacity-40 absolute transform -translate-y-28 " src="https://transferwise.com/staticrab/homepage/_next/static/images/person_20-94244fadaef8decd4751e474258d4eee.jpg" alt="">
                    <img class="image-2 column-1 opacity-40 absolute transform -translate-y-28" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_21-f93c171a0fa20d78a3494740f7547a4b.jpg" alt="">
                    <img class="image-3 column-1 opacity-40 absolute hidden md:block transform -translate-y-28" src="https://transferwise.com/staticrab/homepage/_next/static/images/person_17-bf6d39f644ff4821bbbbe3037475e5a0.jpg" alt="">
                </div>

                <div class="absolute inset-0 w-full flex items-center justify-center">
                    <transition
                enter-active-class="transform transition ease-in-out duration-700"
                enter-class="opacity-0 translate-y-4 scale-0"
                enter-to-class="opacity-100 translate-y-0 scale-100"
                leave-active-class="transform transition ease-in-out duration-700"
                leave-from-class="opacity-100 translate-y-0 scale-100"
                leave-to-class="opacity-0 translate-y-4 scale-0"
                >
                    <img v-show="show" :src="current.src" class=" w-1/2 h-1/2 " alt="">
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
                    src: "https://transferwise.com/staticrab/homepage/_next/static/images/person_8-3579374f699f5fe66c9f949395df90f7.jpg",
                },
                {
                    src: "https://transferwise.com/staticrab/homepage/_next/static/images/person_5-be82fc2ce9ea69c4c325526748211823.jpg"
                },
                {
                    src: "https://transferwise.com/staticrab/homepage/_next/static/images/person_1-c67d50b951a7e1a3d5d72237ade0cf14.jpg"
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
                    }, 4000);
                }else{
                    setTimeout(() => {
                        this.show = true;
                        this.current = this.images[this.currentIndex + 1];
                        this.currentIndex = this.currentIndex + 1
                        this.hideCurrent()
                    }, 4000);
                }
            }
        },
        hideCurrent(){
            setTimeout(() => {
                    this.show = false;
                    this.getCurrent();
            }, 5000);
        }
    }
}
</script>

<style>
    .column-1{
        animation-name: column-1;
        animation-duration: 30s;
        -webkit-animation-duration: 30s;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
        -webkit-font-smoothing: antialiased;
    }
    .column-2{
        animation-name: column-2;
        animation-duration: 30s;
        -webkit-animation-duration: 30s;
        -webkit-font-smoothing: antialiased;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
        animation-direction: reverse
    }

    .column-3{
        animation-name: column-3;
        animation-duration: 30s;
        -webkit-animation-duration: 30s;
        -webkit-font-smoothing: antialiased;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
    }

    .image-1{
        -webkit-animation-delay: 2s;
        animation-delay: 2s;
        vertical-align: middle;
    }

    .image-2{
        -webkit-animation-delay: 30s;
        animation-delay: 20s;
        vertical-align: middle;
    }
    .image-3{
        -webkit-animation-delay: 36s;
        animation-delay: 40s;
        vertical-align: middle;
    }

    .col-3 .image-1{
        -webkit-animation-delay: 0s;
        animation-delay: 0s;
        vertical-align: middle;
    }
    .col-3 .image-2{
        -webkit-animation-delay: 22s;
        animation-delay: 22s;
        vertical-align: middle;
    }
    .col-3 .image-3{
        -webkit-animation-delay: 42s;
        animation-delay: 42s;
        vertical-align: middle;
    }
  

    @keyframes column-1 {
    0%   {left:0px; top:0px;}
    25%  {left:0px; top:25%;}
    50%  {left:0px; top:50%;}
    75%  {left:0px; top:75%;}
    100% {left:0px; top:100%;}
    }

    @keyframes column-3 {
    0%   {left:0px; top:0px;}
    25%  {left:0px; top:25%;}
    50%  {left:0px; top:50%;}
    75%  {left:0px; top:75%;}
    100% {left:0px; top:100%;}
    }

    @keyframes column-2 {
    0%   {left:0px; top:0px;}
    25%  {left:0px; top:25%;}
    50%  {left:0px; top:50%;}
    75%  {left:0px; top:75%;}
    100% {left:0px; top:100%;}
    }
</style>