<template>
    <div class="flex flex-col w-full h-screen md:px-36 px-4 py-4" id="wrapper">

        <!-- Navbar wrapper -->
        <div class="flex flex-row justify-between w-full">

            <!-- Logo div -->
            <div class="flex flex-col ">
                <h1 class="logo text-white lowercase text-3xl">Miracle</h1>
                <p class="tracking-wider text-white position">frontend developer</p>
            </div> 

            <div class="md:hidden flex items-center justify-center">
                <button class="text-white">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
                    </svg>
                </button>
            </div>

            <!-- connect div -->
            <div class="hidden md:flex flex-row justify-center items-start">
                 <button  v-for="tab in tabs" :key="tab.id" class="flex justify-center items-center capitalize my-4 mx-5 text-white connect">
                    <!-- <router-link :to="`${tab.link}`"> -->
                    <span>  {{tab.title}} </span>
                     <!-- </router-link> -->
                </button>

                <div class="relative flex my-2">
                    <div class="absolute inset-0 bg-gradient-to-r from-pink-600 to-purple-600  blur filter opacity-75 rounded-lg hover:opacity-100 transition duration-200"></div>
                 <button class="flex relative py-3 px-4 rounded-lg flex-row capitalize bg-gray-900 leading-none text-white connect">
                    <span class="hover-underline-animation"> Let's talk 
                        <fa :icon="['fas','arrow-right']" class="ml-3" />
                    </span>
                </button>
                </div>
            </div>
        </div>

        <div class="w-full flex md:flex-row flex-col mt-20">
            <div class="flex flex-col">
                <div class="flex flex-row">
                    <p class="text-gray-300 flex justify-center items-center text-2xl md:pl-0 pl-12 py-2 tracking-wider font-semibold open-sans">Holla Welcome,</p>
                    <img src="../assets/hands.png" class="md:w-32 md:h-28 h-28 w-28 flex justify-center items-center waving-hands" alt="hands"/>
                </div>
                <div class="flex flex-row py-7">
                    <div class="flex flex-col justify-center py-8 items-center">
                        <a href="#" class="my-2">
                            <fa :icon="['fab','github']" class="text-2xl text-gray-300"/>
                        </a>
                        <a href="#" class="my-2">
                            <fa :icon="['fab','twitter']" class="text-2xl text-gray-300"/>
                        </a>
                        <a href="#" class="my-2">
                            <fa :icon="['fab','linkedin']" class="text-2xl text-gray-300"/>
                        </a>
                    </div>
                    
                    <div class="md:pr-48 pr-10 pl-7 md:pl-6 flex items-center justify-center">
                        <p class="text-white text-6xl font-bold connect tracking-tighter">I'm Miracle Igbinoghene, a Frontend Developer</p>
                    </div>
                    
                </div>
            </div>

            <transition name="list" mode="out-in" appear>
            <div class="md:w-1/3 w-full md:bg-none bg-gradient-to-r rounded-3xl from-purple-700 to-pink-600 my-4 h-full md:border-none border-4 border-white">
            <div class="flex flex-col justify-center items-center md:justify-end md:items-end py-5">
                <div class="flex flex-col md:text-right text-center">
                    <h1 class="text-white font-semibold text-7xl connect"> 4+ </h1>
                    <p class="tracking-wider font-light text-sm text-white capitalize py-2 connect">Years of<br> experience</p>
                </div>

                <div class="flex flex-col md:text-right text-center py-5">
                    <h1 class="text-white font-semibold text-7xl connect"> 100% </h1>
                    <p class="tracking-wider font-light text-sm text-white capitalize connect py-2">Success rate</p>
                </div>

                <div class="flex flex-col md:text-right text-center py-5">
                    <h1 class="text-white font-semibold text-7xl connect"> 3 </h1>
                    <p class="tracking-wider font-light text-sm text-white capitalize connect py-2">Projects</p>
                </div>
            </div>
            </div>
            </transition>
        </div>

        <!-- second section -->
        <div class="flex flex-col h-screen w-full py-4 my-4">
            <div class="flex flex-col items-center transition-none duration-300 justify-center md:justify-start my-4 md:items-start" id="about">
                <h1 class="font-bold py-1 text-gray-700 tracking-widest text-3xl uppercase " id="about-me">About Me.</h1>
                <div class="w-20 h-2 bg-gradient-to-r rounded-lg from-green-600 to-purple-600"></div>
            </div>
            <div class="flex flex-col md:flex-row">
            <div class="flex flex-col">
              <div class="md:flex flex-row hidden bg-gray-400 w-4/5 h-72 rounded-t-3xl">
                <div class="flex justify-end items-end -mr-60 mb-8">
                    <p class="text-5xl uppercase text-gray-600 font-extrabold px-4"><sup>"</sup>I'm Breathing in creativity.<sup>"</sup></p>
                </div>
                <div class="flex justify-end items-end -ml-16">
                    <img class="flex filter grayscale w-64 h-64" src="../assets/huey-freeman.png">
                </div>
                </div>

                <div class="flex md:w-4/5">
                      <!-- card container -->
                <div class="shadow-lg rounded-br-3xl bg-gray-200">
                    <!-- card  -->
                    <div class="lg:grid flex flex-col-reverse lg:grid-cols-">
                        <div class="lg:col-span-1 md:pt-4 pt-32 w-full md:mt-0 -mt-24" id="text-area">
                            <div class="lg:pl-7">
                            <!-- quote image -->
                            <div class="lg:pl-16 flex lg:justify-start justify-center lg:items-end items-center">
                                <img src="../assets/pattern-quotes.svg" alt="Quotation symbol"  class="w-20">
                            </div>

                            <!-- Text -->
                            <div id="quote" class="lg:px-9 px-5 lg:m-0 lg:mt-0 lg:-mb-16 hover:">
                                <h6 class="text-gray-600 font-semibold pl-4 md:text-xl lg:text-center text-center">
                                    "I'm Miracle a passion driven frontend developer seeking real world experience, open to maintain a full-time position role, while utilizing interpersonal skills, and maximize the power of team work if given the opportunity".
                                </h6>
                            </div>
                            </div>
                            <img src="../assets/pattern-curve.svg" alt="pattern-curve" class="-mt-16">
                        </div>
                        <div class="md:hidden">
                            <!-- Background pattern -->
                            <div class="md:hidden flex justify-center items-center pt-11">
                                <img src="../assets/pattern-bg.svg" alt="pattern-background" class="w-96">
                                <img alt="user-img" src="../assets/me.jpg"  class="w-56 filter grayscale rounded-lg absolute shadow-xl" id="me">
                            </div>
                        </div>
                    </div>
                </div>
                </div>
            </div>    
                <div class="flex-col md:flex w-full md:w-2/12 md:py-0 py-4 items-center justify-center">
                        <div class="flex flex-col w-full justify-center items-center">
                            <h1 class="tracking-tighter font-bold uppercase text-3xl text-gray-600">Skills </h1>
                            <div class="flex justify-center items-center w-5 h-2 bg-gradient-to-r rounded-lg from-green-600 to-purple-600"></div>
                        </div>

                            <div class="flex flex-col items-center justify-center">
                                <div class="flex flex-row md:space-x-5">
                                <div class="flex flex-row justify-center items-center py-3">
                                    <div class="flex flex-col py-2">
                                    <h1 class="uppercase flex justify-center items-center font-semibold tracking-wider text-purple-600">HTML</h1>
                                    <h1 class="uppercase flex justify-center items-center tracking-widest font-bold text-4xl">100%</h1>
                                    </div>
                                </div>

                                <div class="flex flex-row justify-center items-center py-3">
                                    <div class="flex flex-col py-2">
                                    <h1 class="uppercase flex justify-center items-center font-semibold tracking-wider text-purple-600">CSS</h1>
                                    <h1 class="uppercase flex justify-center items-center tracking-widest font-bold text-4xl">98%</h1>
                                    </div>
                                </div>
                                </div>

                                <div class="flex flex-row space-x-5">
                                <div class="flex flex-row justify-center items-center py-3">
                                    <div class="flex flex-col py-2">
                                    <h1 class="uppercase flex justify-center items-center font-semibold tracking-wider text-purple-600">Javascript</h1>
                                    <h1 class="uppercase flex justify-center items-center tracking-widest font-bold text-4xl">70%</h1>
                                    </div>
                                </div>
                                <div class="flex flex-row justify-center items-center py-3">
                                    <div class="flex flex-col py-2">
                                    <h1 class="uppercase flex justify-center items-center font-semibold tracking-wider text-purple-600">tailwind</h1>
                                    <h1 class="uppercase flex justify-center items-center tracking-widest font-bold text-4xl">80%</h1>
                                    </div>
                                </div>
                                </div>

                                <div class="flex flex-row space-x-5">
                                <div class="flex flex-row justify-center items-center py-3">
                                    <div class="flex flex-col py-2">
                                    <h1 class="uppercase flex justify-center items-center font-semibold tracking-wider text-purple-600">Vue.js</h1>
                                    <h1 class="uppercase flex justify-center items-center tracking-widest font-bold text-4xl">70%</h1>
                                    </div>
                                </div>
                                <div class="flex flex-row justify-center items-center py-3">
                                    <div class="flex flex-col py-2">
                                    <h1 class="uppercase flex justify-center items-center font-semibold tracking-wider text-purple-600">sass</h1>
                                    <h1 class="uppercase flex justify-center items-center tracking-widest font-bold text-4xl">70%</h1>
                                    </div>
                                </div>
                                </div>

                                <div class="flex flex-row space-x-5">
                                <div class="flex flex-row justify-center items-center py-3">
                                    <div class="flex flex-col py-2">
                                    <h1 class="uppercase flex justify-center items-center font-semibold tracking-wider text-purple-600">Bootstrap</h1>
                                    <h1 class="uppercase flex justify-center items-center tracking-widest font-bold text-4xl">80%</h1>
                                    </div>
                                </div>
                                <div class="flex flex-row justify-center items-center py-3">
                                    <div class="flex flex-col py-2">
                                    <h1 class="uppercase flex justify-center items-center font-semibold tracking-wider text-purple-600">git</h1>
                                    <h1 class="uppercase flex justify-center items-center tracking-widest font-bold text-4xl">60%</h1>
                                    </div>
                                </div>
                                </div>
                            </div>
                        </div>
                </div>
            </div>
</div>
</template>

<script>
export default {
    name: 'Home',
    components: {
    },
    data (){
        return{
                tabs: [
                {title: 'About me', id:'about', link:'../views/About'},
                {title: 'Blogs', id:'blogs', link: '../views/Blogs'},
                {title: 'Projects.', id:'projects', link: '../views/Projects'},
            ]
        }
    }

}
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Monoton&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');

    #wrapper {
        background: #0f0c29;  /* fallback for old browsers */
        background: -webkit-linear-gradient(to right, #24243e, #302b63, #0f0c29);  /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to right, #24243e, #302b63, #0f0c29); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    }

    .logo {
        font-family: 'Monoton', cursive;
    }

    .position {
        font-family: 'Kanit', sans-serif;
    }

    .connect {
        font-family: 'Montserrat', sans-serif;
    }

    .open-sans {
        font-family: 'Open Sans', sans-serif;
    }

    /* Hands wave animation  */
    .waving-hands {
        -webkit-animation: shake 1s ease-in-out infinite alternate;
    }

    @-webkit-keyframes shake{
        from {
            -webkit-transform: rotate(15deg);
        }
        to {
            -webkit-transform: rotate(-15deg);
            -webkit-transform-origin: center center;
        }
    }

        #quote {
        position: relative;
        top: -20px;
    }

    .list-enter-from{
  opacity: 0;
  transform: translateX(180px);
}
    .list-enter-active{
  transition: all 0.3s ease-out;
}

    .list-leave-to{
   opacity: 0;
   transform: translateX(-180px);
}

    .list-leave-active {
  transition: all 0.3s ease-in;
}

    .text-in-enter-from{
  opacity: 0;
  transform: translateY(-180px);
}
    .text-in-enter-active{
  transition: all 0.3s ease-out;
}

    .text-in-leave-to{
   opacity: 0;
   transform: translateY(180px);
}

    .text-in-leave-active {
  transition: all 0.3s ease-in;
}
</style>