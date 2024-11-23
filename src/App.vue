<script setup>
import { VueMarqueeSlider } from "./components/";
</script>

<template>
<div class="bg-slate-50">
    <div class="py-16 mb-24">
        <div class="container max-w-screen-xl mx-auto px-4">
            <nav class="flex-wrap flex items-center justify-center lg:justify-between mb-24 xl:mb-32 xl:mx-0 md:mx-14">
                <div class="flex items-center mb-10 lg:mb-0">
                    <a href="#"><img class="w-16" src="/src/assets/images/A-Logo-colored.png" alt="Logo" v-motion-pop-visible></a>
                </div>

                <ul class="hidden flex-col lg:flex-row lg:flex lg:items-center lg:space-x-20 mb-10 xl:mb-0" v-motion-slide-visible-top>
                    <li class="font-medium text-gray-500 text-lg hover:text-orange-500 transiton ease-in-out duration-300 mb-5 lg:mb-0">
                        <a href="">Home</a>
                    </li>
                    <li class="font-medium text-gray-500 text-lg hover:text-orange-500 transiton ease-in-out duration-300 mb-5 lg:mb-0">
                        <a href="#education">Education</a>
                    </li>
                    <li class="font-medium text-gray-500 text-lg hover:text-orange-500 transiton ease-in-out duration-300 mb-5 lg:mb-0">
                        <a href="#skills">Skills</a>
                    </li>
                    <li class="font-medium text-gray-500 text-lg hover:text-orange-500 transiton ease-in-out duration-300 mb-5 lg:mb-0">
                        <a href="#work">Work</a>
                    </li>
                    <li class="px-8 py-3 font-medium text-orange-500 text-lg text-center border-2 border-orange-500 rounded-md hover:bg-orange-500 hover:text-white transiton ease-linear duration-300">
                        <a href="#contacts">Contacts</a>
                    </li>
                </ul>
            </nav>

            <div class="flex flex-col lg:flex-row justify-around lg:mb-20">
                <div class="mx-auto lg:mx-0" v-motion-slide-visible-left>
                    <img class="max-h-96" src="/src/assets/images/aying3.jpg" alt="">
                </div>

                <div class="text-center lg:text-left mb-20 mt-10 lg:mb-0"  v-motion-slide-visible-right>
                    <div class="flex items-center justify-center lg:justify-start gap-4 mb-10">
                        <span class="w-10 h-0.5 bg-orange-500"></span>
                        <p class="font-medium text-orange-500 text-xl">Leoneil Ivan Aying</p>
                    </div>

                    <h1 class="font-bold text-gray-800 text-4xl md:text-6xl xl:text-7xl mb-10">
                        Digital Artist <br/>
                    </h1>

                    <p class="font-normal text-gray-500 text-sm md:text-md xl:text-lg mb-10">
                        Hi, I’m Ying. I’m an Illustrator and an UI/UX Designer.<br />
                        Let's make your imaginations run wild!<br />
                    </p>

                    <hr class="text-gray-500 mb-5" />
                </div>
            </div>
        </div>
    </div>

    <div id="education" class="pt-10">
        <p class="font-bold text-gray-800 text-4xl md:text-5xl xl:text-6xl text-center leading-tight mb-20 xl:mb-20" v-motion-slide-visible-top>
                Education
        </p>
        
        <div class="mx-20 my-10 mb-40">

            <div class="container mx-auto w-full h-full">
            <div class="relative wrap overflow-hidden p-10 h-full">
                <div class="absolute border-orange-500 h-full border-4 left-1/2 transform -translate-x-1/2"></div>
                <!-- right timeline -->
                <div class="mb-16 flex justify-between flex-row-reverse items-center w-full left-timeline" v-motion-slide-visible-left>
                <div class="order-1 w-5/12"></div>
                <div class="z-20 flex items-center order-1 w-24 h-24 rounded-full bg-slate-50" v-motion-pop-visible>
                    <img class="w-full h-full object-contain block" src="/src/assets/images/csu.png" alt=""/>
                </div>
                <div class="absolute left-1/2 ml-16">
                    <p class="font-bold text-gray-500">2022 - Present</p>
                </div>
                <div class="order-1 bg-white rounded-lg shadow-md w-5/12 px-6 py-4 border-b-orange-500 border-b-4">
                    <h3 class="mb-3 font-bold text-orange-500 text-xl">Bachelor of Science in Information Technology</h3>
                    <p class="mb-3 font-bold text-gray-800 text-sm">Caraga State University</p>
                    <ul class="list-disc text-sm leading-snug tracking-wide text-gray-500 mx-4">
                    <li>Courses undertaken: Integrative Programming and Technologies, Web Systems and Technologies, 
                    Systems Integration and Architecture, Advanced Database Management System, and Information 
                    Assurance and Security.</li>
                    </ul>
                </div>
                </div>

                <!-- left timeline -->
                <div class="mb-8 flex justify-between items-center w-full left-timeline" v-motion-slide-visible-right>
                <div class="order-1 w-5/12"></div>
                <div class="z-20 flex items-center order-1 w-24 h-24 rounded-full bg-slate-50">
                    <img class="w-full h-full object-contain block" src="/src/assets/images/anhs.png" alt=""/>
                </div>
                <div class="absolute right-1/2 mr-16">
                    <p class="font-bold text-gray-500">2019 - 2021</p>
                </div>
                <div class="order-1 bg-white rounded-lg shadow-md w-5/12 px-6 py-4 border-b-orange-500 border-b-4">
                    <h3 class="mb-3 font-bold text-orange-500 text-xl">Science, Technology, Engineering, and Mathematics</h3>
                    <p class="mb-3 font-bold text-gray-800 text-sm">Agusan National High School - Senior High School</p>
                    <ul class="list-disc text-sm leading-snug tracking-wide text-gray-500 mx-4">
                    <li>12th Grade: w/ Highest Honors</li>
                    <li>11th Grade: w/ High Honors</li>
                    </ul>
                </div>
                </div>

                
            </div>
            </div>
        </div>
    </div>
<div id="skills" class="pt-10">
    <p class="font-bold text-gray-800 text-4xl md:text-5xl xl:text-6xl text-center leading-tight mb-10 xl:mb-20" v-motion-slide-visible-once-top>
                Skills
    </p>
    
    <vue-marquee-slider id="marquee-slider-loop" :speed="22500" class="bg-slate-100 py-10 icons-saturate my-32" v-motion-slide-visible-once-right>
        <img src="/src/assets/images/html.png" alt="">
        <img src="/src/assets/images/css.png" alt="">
        <img src="/src/assets/images/javascript.png" alt="">
        <img src="/src/assets/images/bootstrap.png" alt="">
        <img src="/src/assets/images/tailwind2.png" alt="">
        <img src="/src/assets/images/c.png" alt="">
        <img src="/src/assets/images/java.png" alt="">
        <img src="/src/assets/images/python.png" alt="">
        <img src="/src/assets/images/nodejs.png" alt="">
        <img src="/src/assets/images/vuejs.png" alt="">
        <img src="/src/assets/images/reactjs.png" alt="">
        <img src="/src/assets/images/pgsql.png" alt="">
        <img src="/src/assets/images/mysql.png" alt="">
    </vue-marquee-slider>
</div>

    <div class="py-10 lg:mb-20" id="work">
        <div class="container max-w-screen-xl mx-auto px-4">

            <p class="font-bold text-gray-800 text-4xl md:text-5xl xl:text-6xl text-center leading-tight mb-20 xl:mb-20" v-motion-slide-visible-once-top>
                Work<br/>
            </p>

            <div class="flex flex-col xl:flex-row gap-16">
                <div class="grid grid-cols-2 text-center xl:text-left xl:gap-x-24 mt-10">
                    <div class="mb-16 xl:mb-0" v-motion-pop-visible-once>
                        <h4 class="font-semibold text-gray-800 text-md md:text-lg mb-5">
                            Illustrator
                        </h4>

                        <p class="font-normal text-gray-500 text-xs md:text-sm mb-5">
                            A creative professional who combines hand-drawing and painting with digital media to produce visually captivating illustrations.<br/>
                        </p>

                        <a href="#" class="flex items-center justify-center xl:justify-start gap-3 font-medium text-orange-500 text-md hover:text-indigo-600 transition ease-in-out duration-300">
                            See Works
                            <i data-feather="arrow-right"></i>
                        </a>
                    </div>

                    <div class="mb-16 xl:mb-0" v-motion-pop-visible-once>
                        <h4 class="font-semibold text-gray-800 text-md md:text-lg mb-5">
                            Animator
                        </h4>

                        <p class="font-normal text-gray-500 text-xs md:text-sm mb-5">
                            I bring stories and characters to life through movement and expression. My work revolves around creating dynamic visuals that convey emotion, personality, and narrative flow.<br/>
                        </p>

                        <a href="#" class="flex items-center justify-center xl:justify-start gap-3 font-medium text-orange-500 text-md hover:text-indigo-600 transition ease-in-out duration-300">
                            See Works
                            <i data-feather="arrow-right"></i>
                        </a>
                    </div>

                    <div class="mb-16 xl:mb-0" v-motion-pop-visible-once>
                        <h4 class="font-semibold text-gray-800 text-md md:text-lg mb-5">
                            Mobile Design
                        </h4>

                        <p class="font-normal text-gray-500 text-xs md:text-sm mb-5">
                            Focuses on creating intuitive, engaging, and visually appealing user experiences specifically for mobile devices.<br />
                        </p>

                        <a href="#" class="flex items-center justify-center xl:justify-start gap-3 font-medium text-orange-500 text-md hover:text-indigo-600 transition ease-in-out duration-300">
                            See Works
                            <i data-feather="arrow-right"></i>
                        </a>
                    </div>

                    <div class="mb-16 xl:mb-0" v-motion-pop-visible-once>
                        <h4 class="font-semibold text-gray-800 text-md md:text-lg mb-5">
                            Web Design
                        </h4>

                        <p class="font-normal text-gray-500 text-xs md:text-sm mb-5">
                            Creates visual layouts and aesthetics, focusing on user experience, graphics, and overall look.<br />
                        </p>

                        <a href="#" class="flex items-center justify-center xl:justify-start gap-3 font-medium text-orange-500 text-md hover:text-indigo-600 transition ease-in-out duration-300">
                            See Works
                            <i data-feather="arrow-right"></i>
                        </a>
                    </div>
                </div>

                <div class="mx-auto xl:mx-0" v-motion-slide-visible-once-right>
                    <img class="" src="/src/assets/images/16.png" alt=""/>
                </div>
            </div>
        </div>
    </div>

    <div>
        <h1 class="font-semibold text-gray-800 text-2xl md:text-3xl xl:text-5xl text-center leading-tight mb-20 xl:mb-40" v-motion-slide-visible-right>
                From dreams<br />
                <span class="text-orange-500">to reality<br /></span>
            </h1>
    </div>

    <div class="bg-slate-100" id="contacts">
        <div class="py-8 lg:py-16 px-4 mx-auto max-w-screen-md">
            <h2 class="font-bold text-gray-800 text-4xl md:text-5xl xl:text-6xl text-center leading-tight mb-20 xl:mb-20" v-motion-slide-visible-top>Contact Me</h2>
            <form action="#" class="space-y-8" v-motion-slide-visible-left>
                <div>
                    <label for="email" class="block mb-2 text-sm font-medium text-orange-500">Email</label>
                    <input type="email" id="email" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg block w-full p-2.5 focus:ring-2 focus:outline-none focus:ring-orange-500" placeholder="Your email" required>
                </div>
                <div>
                    <label for="subject" class="block mb-2 text-sm font-medium text-orange-500">Subject</label>
                    <input type="text" id="subject" class="block p-3 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-2 focus:outline-none focus:ring-orange-500" placeholder="Let me know how I can help you" required>
                </div>
                <div class="sm:col-span-2">
                    <label for="message" class="block mb-2 text-sm font-medium text-orange-500">Your message</label>
                    <textarea id="message" rows="6" class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg shadow-sm border border-gray-300 focus:ring-2 focus:outline-none focus:ring-orange-500" placeholder="Leave a comment..."></textarea>
                </div>
                <button type="submit" class="py-3 px-5 text-sm font-medium text-center text-orange-500 hover:text-white rounded-lg sm:w-fit border-orange-500 border-2 hover:bg-orange-500 ">Send message</button>
            </form>
        </div>
    </div>

    <footer class="bg-orange-500 py-16">
        <div class="container max-w-screen-xl mx-auto px-4">
        </div>
    </footer>

</div>
</template>

<style scoped>
</style>
