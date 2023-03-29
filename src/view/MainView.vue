<script setup></script>

<template>
  <div class="flex justify-between">
    <img src="../assets/logo.svg" alt="" />
    <div class="flex flex-row">
      <div class="flex flex-row items-center">
        <p class="font-medium mr-2">Sans</p>
        <img src="../assets/icon-arrow-down.svg" alt="" />
      </div>
      <div class="flex items-center ml-5">
        <label class="relative inline-flex items-center cursor-pointer">
          <input type="checkbox" value="" class="sr-only peer" peer />
          <div
            class="w-11 h-6 bg-gray-200 rounded-full peer peer-focus:ring-4 peer-focus:ring-blue-300 dark:peer-focus:ring-blue-800 dark:bg-gray-700 peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:left-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-blue-600"
          ></div>
          <img class="ml-2" src="../assets/icon-moon.svg" alt="" />
        </label>
      </div>
    </div>
  </div>
  <div
    for="search"
    class="w-full bg-slate-200 my-6 h-12 rounded-xl flex flex-row justify-between p-4"
  >
    <input
      id="search"
      name="search"
      type="text"
      class="appearance-none border-none bg-transparent focus:outline-none w-full"
    />
    <img src="../assets/icon-search.svg" alt="" />
  </div>
  <div class="flex justify-between items-center">
    <div>
      <p class="font-bold text-[40px]">Keybord</p>
      <p class="text-blue-600">pronunciacion</p>
    </div>
    <img class="h-[50px]" src="../assets/icon-play.svg" alt="" />
  </div>
  <div class="flex flex-row items-center my-4">
    <p class="mr-2 font-semibold">noun</p>
    <div class="bg-slate-200 w-full h-[1px] mt-1"></div>
  </div>
  <p class="text-slate-400 mb-2">Meaning</p>
  <div class="flex flex-row">
    <div class="h-[14px] w-[14px] mr-5">
      <div class="h-[6px] w-[6px] bg-blue-500 rounded-full mt-[8px]"></div>
    </div>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, vel?
    </p>
  </div>
  <div class="flex flex-row my-8">
    <p class="mr-5">Synonymus</p>
    <p class="text-blue-500">El sinonimo jsjsjssj</p>
  </div>
  <div class="flex flex-row items-center my-4">
    <p class="mr-2 font-semibold">verb</p>
    <div class="bg-slate-200 w-full h-[1px] mt-1"></div>
  </div>
  <p class="text-slate-400 mb-2">Meaning</p>
  <div class="flex flex-row">
    <div class="h-[14px] w-[14px] mr-5">
      <div class="h-[6px] w-[6px] bg-blue-500 rounded-full mt-[8px]"></div>
    </div>
    <div>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, vel?
      </p>
      <p class="my-3 text-slate-500">
        "Lorem ipsum dolor sit amet consectetur, adipisicing elit."
      </p>
    </div>
  </div>
  <div class="bg-slate-200 w-full h-[1px] my-4"></div>
  <p class="text-slate-500 text-sm">Source</p>
  <div class="flex flex-row mt-2 text-sm">
    <a
      class="underline underline-offset-2 cursor-pointer"
      href="https://en.wiktionary.org/wiki/palabra"
      >https://en.wiktionary.org/wiki/palabra</a
    >
    <img class="ml-2" src="../assets/icon-new-window.svg" alt="" />
  </div>
</template>
