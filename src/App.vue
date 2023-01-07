<script setup>
import image from './assets/myimage.jpg'
</script>

<template>
  <div class="max-w-7xl mx-auto sm:p-10">
    <div class="max-w-3xl mx-auto w-full">
      <div class="sm:my-32 my-10">
        <div >
          <div class="grid justify-center gap-4">
          <img :src="image" class="h-40 rounded-full mx-auto " alt="">
          <h1 class="text-center text-3xl sm:text-4xl sm:tracking-widest uppercase font-extrabold text-teal-300">
            Norjamille Kasan
          </h1>
          <span class="text-center text-white text-xl font-semibold">
            Full Stack Web Developer 
          </span>
          <div class="flex justify-center space-x-6 pt-5">
            <a href="#" class="group">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="h-8  rounded-sm  fill-white">
                <path fill="none" d="M0 0h24v24H0z" />
                <path
                  d="M22.162 5.656a8.384 8.384 0 0 1-2.402.658A4.196 4.196 0 0 0 21.6 4c-.82.488-1.719.83-2.656 1.015a4.182 4.182 0 0 0-7.126 3.814 11.874 11.874 0 0 1-8.62-4.37 4.168 4.168 0 0 0-.566 2.103c0 1.45.738 2.731 1.86 3.481a4.168 4.168 0 0 1-1.894-.523v.052a4.185 4.185 0 0 0 3.355 4.101 4.21 4.21 0 0 1-1.89.072A4.185 4.185 0 0 0 7.97 16.65a8.394 8.394 0 0 1-6.191 1.732 11.83 11.83 0 0 0 6.41 1.88c7.693 0 11.9-6.373 11.9-11.9 0-.18-.005-.362-.013-.54a8.496 8.496 0 0 0 2.087-2.165z" />
              </svg>
            </a>

            <a href="#" class="group">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="h-8  rounded-sm  fill-white">
                <path fill="none" d="M0 0h24v24H0z" />
                <path
                  d="M12 2C6.477 2 2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.879V14.89h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.989C18.343 21.129 22 16.99 22 12c0-5.523-4.477-10-10-10z" />
              </svg>
            </a>
            <a href="#" class="group">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="h-8  rounded-sm  fill-white">
                <path fill="none" d="M0 0h24v24H0z" />
                <path
                  d="M18.335 18.339H15.67v-4.177c0-.996-.02-2.278-1.39-2.278-1.389 0-1.601 1.084-1.601 2.205v4.25h-2.666V9.75h2.56v1.17h.035c.358-.674 1.228-1.387 2.528-1.387 2.7 0 3.2 1.778 3.2 4.091v4.715zM7.003 8.575a1.546 1.546 0 0 1-1.548-1.549 1.548 1.548 0 1 1 1.547 1.549zm1.336 9.764H5.666V9.75H8.34v8.589zM19.67 3H4.329C3.593 3 3 3.58 3 4.297v15.406C3 20.42 3.594 21 4.328 21h15.338C20.4 21 21 20.42 21 19.703V4.297C21 3.58 20.4 3 19.666 3h.003z" />
              </svg>
            </a>
          </div>
        </div>

        </div>
        <div class=" pt-5 grid gap-10">
          <div id="about"
            class="p-5 hover:shadow-lg rounded-lg duration-150 border border-transparent hover:border-teal-400 hover:shadow-teal-400">
            <div class="grid gap-3">
              <h1 class="uppercase text-teal-300 font-semibold text-2xl">
                About
              </h1>
              <p class="text-white ind">
                Hi there 👋 ! I'm a full stack web developer with a passion for building beautiful and user-friendly
                web applications. I have experience building application with Laravel , VueJS, InertiaJS, Livewire
                AlpineJS
                , and Tailwind CSS. I am always eager to learn new technologies and expand my skillset.
              </p>
            </div>
          </div>

          <div id="stack"
            class="p-5 hover:shadow-lg rounded-lg duration-150 border border-transparent hover:border-teal-400 hover:shadow-teal-400">
            <div class="grid gap-3">
              <h1 class="uppercase text-teal-300 font-semibold text-2xl">
                Tech Stack
              </h1>
              <div class="sm:grid sm:grid-cols-2 gap-5">
                <!--  -->
                <div class="sm:col-span-1 flex space-x-4 items-center">
                  <svg class="h-12" viewBox="0 0 50 52" xmlns="http://www.w3.org/2000/svg">
                    <title>Logomark</title>
                    <path
                      d="M49.626 11.564a.809.809 0 0 1 .028.209v10.972a.8.8 0 0 1-.402.694l-9.209 5.302V39.25c0 .286-.152.55-.4.694L20.42 51.01c-.044.025-.092.041-.14.058-.018.006-.035.017-.054.022a.805.805 0 0 1-.41 0c-.022-.006-.042-.018-.063-.026-.044-.016-.09-.03-.132-.054L.402 39.944A.801.801 0 0 1 0 39.25V6.334c0-.072.01-.142.028-.21.006-.023.02-.044.028-.067.015-.042.029-.085.051-.124.015-.026.037-.047.055-.071.023-.032.044-.065.071-.093.023-.023.053-.04.079-.06.029-.024.055-.05.088-.069h.001l9.61-5.533a.802.802 0 0 1 .8 0l9.61 5.533h.002c.032.02.059.045.088.068.026.02.055.038.078.06.028.029.048.062.072.094.017.024.04.045.054.071.023.04.036.082.052.124.008.023.022.044.028.068a.809.809 0 0 1 .028.209v20.559l8.008-4.611v-10.51c0-.07.01-.141.028-.208.007-.024.02-.045.028-.068.016-.042.03-.085.052-.124.015-.026.037-.047.054-.071.024-.032.044-.065.072-.093.023-.023.052-.04.078-.06.03-.024.056-.05.088-.069h.001l9.611-5.533a.801.801 0 0 1 .8 0l9.61 5.533c.034.02.06.045.09.068.025.02.054.038.077.06.028.029.048.062.072.094.018.024.04.045.054.071.023.039.036.082.052.124.009.023.022.044.028.068zm-1.574 10.718v-9.124l-3.363 1.936-4.646 2.675v9.124l8.01-4.611zm-9.61 16.505v-9.13l-4.57 2.61-13.05 7.448v9.216l17.62-10.144zM1.602 7.719v31.068L19.22 48.93v-9.214l-9.204-5.209-.003-.002-.004-.002c-.031-.018-.057-.044-.086-.066-.025-.02-.054-.036-.076-.058l-.002-.003c-.026-.025-.044-.056-.066-.084-.02-.027-.044-.05-.06-.078l-.001-.003c-.018-.03-.029-.066-.042-.1-.013-.03-.03-.058-.038-.09v-.001c-.01-.038-.012-.078-.016-.117-.004-.03-.012-.06-.012-.09v-.002-21.481L4.965 9.654 1.602 7.72zm8.81-5.994L2.405 6.334l8.005 4.609 8.006-4.61-8.006-4.608zm4.164 28.764l4.645-2.674V7.719l-3.363 1.936-4.646 2.675v20.096l3.364-1.937zM39.243 7.164l-8.006 4.609 8.006 4.609 8.005-4.61-8.005-4.608zm-.801 10.605l-4.646-2.675-3.363-1.936v9.124l4.645 2.674 3.364 1.937v-9.124zM20.02 38.33l11.743-6.704 5.87-3.35-8-4.606-9.211 5.303-8.395 4.833 7.993 4.524z"
                      fill="#FF2D20" fill-rule="evenodd" />
                  </svg>
                  <h1 class="text-white font-bold text-2xl">
                    Laravel
                  </h1>
                </div>
                <!--  -->
                <div class="sm:col-span-1 flex space-x-4 items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-12" viewBox="0 0 24 24">
                    <path d="m1.026 23.567-.001-.008-.001-.003z" />
                    <path fill="#41B883" d="m0 1.65 12 20.7 12-20.7h-4.8L12 14.07 4.74 1.65H0z" />
                    <path fill="#35495E" d="M4.74 1.65 12 14.13l7.2-12.48h-4.44L12 6.45l-2.82-4.8H4.74z" />
                  </svg>
                  <h1 class="text-white font-bold text-2xl">
                    Vue JS
                  </h1>
                </div>
                <!--  -->
                <div class="sm:col-span-1 flex space-x-4 items-center">
                  <img src="https://avatars.githubusercontent.com/u/51960834?s=100" class="h-12" alt="">
                  <h1 class="text-white font-bold text-2xl">
                    Livewire
                  </h1>
                </div>
                <!--  -->
                <div class="sm:col-span-1 flex space-x-4 items-center">
                  <img src="https://avatars.githubusercontent.com/u/47703742?s=200&v=4" class="h-12" alt="">
                  <h1 class="text-white font-bold text-2xl">
                    Inertai JS
                  </h1>
                </div>
                <!--  -->
                <div class="sm:col-span-1 flex space-x-4 items-center">
                  <svg viewBox="0 0 45.116 22.806" xmlns="http://www.w3.org/2000/svg" class="h-8">
                    <g opacity=".8">
                      <path d="M33.71 0L11.207 22.693l.113.113h22.586l11.21-11.304z" fill="#d8dee9" />
                      <path d="M11.405 0l22.578 22.769-.039.037H11.209L0 11.502z" fill="#8ac0cf" />
                    </g>
                  </svg>
                  <h1 class="text-white font-bold text-2xl">
                    Alpine JS
                  </h1>
                </div>
                <div class="sm:col-span-1 flex space-x-4 items-center">
                  <svg class="h-10" viewBox="0 0 256 154" version="1.1" xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="xMidYMid">
                    <defs>
                      <linearGradient x1="-2.77777778%" y1="32%" x2="100%" y2="67.5555556%" id="linearGradient-1">
                        <stop stop-color="#2298BD" offset="0%"></stop>
                        <stop stop-color="#0ED7B5" offset="100%"></stop>
                      </linearGradient>
                    </defs>
                    <g>
                      <path
                        d="M128,-1.0658141e-14 C93.8666667,-1.0658141e-14 72.5333333,17.0666667 64,51.2 C76.8,34.1333333 91.7333333,27.7333333 108.8,32 C118.537481,34.4343704 125.497363,41.4985481 133.201067,49.3184 C145.750756,62.0567704 160.275437,76.8 192,76.8 C226.133333,76.8 247.466667,59.7333333 256,25.6 C243.2,42.6666667 228.266667,49.0666667 211.2,44.8 C201.462519,42.3656296 194.502637,35.3014519 186.798933,27.4816 C174.249244,14.7432296 159.724563,-1.0658141e-14 128,-1.0658141e-14 Z M64,76.8 C29.8666667,76.8 8.53333333,93.8666667 0,128 C12.8,110.933333 27.7333333,104.533333 44.8,108.8 C54.5374815,111.23437 61.497363,118.298548 69.2010667,126.1184 C81.7507556,138.85677 96.275437,153.6 128,153.6 C162.133333,153.6 183.466667,136.533333 192,102.4 C179.2,119.466667 164.266667,125.866667 147.2,121.6 C137.462519,119.16563 130.502637,112.101452 122.798933,104.2816 C110.249244,91.5432296 95.724563,76.8 64,76.8 Z"
                        fill="url(#linearGradient-1)"></path>
                    </g>
                  </svg>
                  <h1 class="text-white font-bold text-2xl">
                    Tailwind CSS
                  </h1>
                </div>
              </div>
            </div>
          </div>

          <div id="contact"
            class="p-5 hover:shadow-lg rounded-lg duration-150 border border-transparent hover:border-teal-400 hover:shadow-teal-400">
            <div class="grid gap-3">
              <h1 class="uppercase text-teal-300 font-semibold text-2xl">
                Contact me
              </h1>
              <p class="text-white ind">
                  Email : norjamille.kasan@gmail.com
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


