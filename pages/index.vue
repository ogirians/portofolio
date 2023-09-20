<template>
  <!-- <Tutorial/> -->
  <!-- <Main/> -->
  <div class="relative bg-slate-900 p-4 min-h-screen">
    <div class="bg-slate-600 p-2 flex flex-row flex-wrap xl:flex-nowrap rounded-lg">
        <div class="grow xl:basis-1/2 relative rounded-xl  m-2">
          <div class="text-white text-left text-7xl font-sans font-bold bg-slate-500 rounded-xl p-2">
            Bringing Your Ideas To Life Through UI Design
            <div class="pt-5 -mt-2 flex items-center justify-end">
              <button class="rounded-xl p-2 bg-purple-600 text-sm hover:bg-purple-800 flex items-center">
                <span class="inline">
                  hire me
                </span>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 ml-1">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M10.05 4.575a1.575 1.575 0 10-3.15 0v3m3.15-3v-1.5a1.575 1.575 0 013.15 0v1.5m-3.15 0l.075 5.925m3.075.75V4.575m0 0a1.575 1.575 0 013.15 0V15M6.9 7.575a1.575 1.575 0 10-3.15 0v8.175a6.75 6.75 0 006.75 6.75h2.018a5.25 5.25 0 003.712-1.538l1.732-1.732a5.25 5.25 0 001.538-3.712l.003-2.024a.668.668 0 01.198-.471 1.575 1.575 0 10-2.228-2.228 3.818 3.818 0 00-1.12 2.687M6.9 7.575V12m6.27 4.318A4.49 4.49 0 0116.35 15m.002 0h-.002" />
                </svg>
              </button>
            </div>
          </div>
          <div class="flex flex-row flex-wrap sm:flex-nowrap rounded-xl mt-3">
            <div class="grow sm:basis-1/3 w-full h-40 bg-cyan-400 my-1 sm:mx-1 sm:my-0 rounded-xl flex items-center justify-center">
              <div class="text-5xl text-center font-sans font-bold text-white items-center justify-center">
                <span>2+</span><br>
                <!-- <a class="text-lg">year</a>   -->
                <div class="text-sm font-thin">Year Experience</div>
              </div>
            </div>
            <div class="grow sm:basis-1/3 w-full h-40  bg-orange-400 my-1 sm:mx-1 sm:my-0 rounded-xl flex items-center justify-center">
              <div class="text-5xl text-center font-sans font-bold text-black items-center justify-center">
                <span>20+</span><br>
                <!-- <a class="text-lg">year</a>   -->
                <div class="text-sm font-thin">Projects completed</div>
              </div>
            </div>
            <div class="grow sm:basis-1/3 w-full h-40  bg-pink-400 my-1 sm:mx-1 sm:my-0 rounded-xl flex items-center justify-center">
              <div class="text-5xl text-center font-sans font-bold text-white items-center justify-center">
                <span>15+</span><br>
                <!-- <a class="text-lg">year</a>   -->
                <div class="text-sm font-thin">Clients</div>
              </div>
            </div>
          </div>
        </div>
        <div class="grow xl:basis-1/2 relative rounded-xl  m-2">
          <div class="xl:h-1/6 min-h-fit p-2 text-white flex flex-row text-md font-sans bg-slate-500 rounded-xl">
            <div class="px-2 grow md:basis-1/2 flex justify-start font-semibold items-center">
              Profile
            </div>
            <div class="px-2 grow md:basis-1/2 flex justify-end items-center">
              <div class="relative">
                <button @click="menu = !menu">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                  </svg>
                </button>
                <div v-show="menu" class="absolute w-32 bg-white rounded-md top-6 right-1 divide-y-2">
                  <div class="text-black p-3 hover:bg-slate-200 rounded-md">
                    Menu 1
                  </div>
                  <div class="text-black p-3 hover:bg-slate-200 rounded-md">
                    menu 2
                  </div>
                  <div class="text-black p-3 hover:bg-slate-200 rounded-md">
                    Menu 3
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="flex h-60 xl:h-5/6 flex-row flex-wrap md:flex-nowrap ">
            <div class="basis-1/2 bg-white  rounded-xl p-2 mt-4">
              ds
            </div>
          </div>
        </div>
    </div>
  </div>
  <!-- <div></div> -->
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return{
      menu : false,
    }
  }
}
</script>

<style>
</style>
