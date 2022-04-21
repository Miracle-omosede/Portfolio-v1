<template>
 <!-- second section -->
        <div class="flex flex-col h-screen w-full py-4 px-6 my-4" id="aboutme" >
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
                            <div id="quote"  class="lg:px-9 px-5 lg:m-0 lg:mt-0 lg:-mb-16 hover:">
                                <h6 class="text-gray-600 font-semibold pl-4 md:text-xl lg:text-center text-center z-50 connect">
                                    "I'm Miracle a passion driven frontend developer seeking real world experience, open to maintain a full-time position role, while utilizing interpersonal skills, and maximize the power of team work if given the opportunity".
                                </h6>
                            </div>
                            </div>
                            <img  src="../assets/pattern-curve.svg" alt="pattern-curve" class="-mt-16">
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
                <div class="flex-col md:flex w-full md:w-2/12 md:py-0 py-4 items-center justify-center connect">
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
</template>


<script>
export default {
  name: 'About',
  components: {

  }
}
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
       
        #quote {
        position: relative;
        top: -20px;
    }

        .connect {
        font-family: 'Montserrat', sans-serif;
    }
</style>