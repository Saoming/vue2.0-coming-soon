<!-- prettier-ignore -->
<template>
  <client-only>
    <vac :end-time="new Date(Date.parse(new Date()) + 114 * 24 * 60 * 60 * 1000)">
      <span slot="process" slot-scope="{ timeObj }" class="text-5xl">
        <div class="flex flex-wrap justify-between w-full items-center mb-10">

          <div class="text-center">
            <div class="mt-2 p-5 w-40 rounded-lg shadow-xl">
              <span class="bg-special-2 p-8">{{`${timeObj.d}`}} </span>
              <!-- <span class="unit px-4"> : </span>  -->
            </div>
            <div class="mt-2 px-5 w-40 text-sm uppercase font-bold"> Days </div>
          </div>

          <div class="text-center">
            <div class="mt-2 p-5 w-40 rounded-lg shadow-xl">
              <span class="bg-special-2 p-8">{{`${timeObj.h}`}} </span>
              <!-- <span class="unit px-4"> : </span>   -->
            </div>
            <div class="mt-2 px-5 w-40 text-sm uppercase font-bold"> Hours </div>

          </div>

          <div class="text-center">
            <div class="mt-2 p-5 w-40 rounded-lg shadow-xl">
                <span class="bg-special-2  p-8">{{`${timeObj.m}`}} </span>
                <!-- <span class="unit px-4"> : </span>  -->
            </div>
            <div class="mt-2 px-5 w-40 text-sm uppercase font-bold"> Minutes </div>
          </div>
          
          <div class="text-center">
            <div class="mt-2 p-5 w-40 rounded-lg shadow-xl">
              <span class="bg-special-2 p-8">{{`${timeObj.s}`}} </span>
            </div>
            <div class="mt-2 px-5 w-40 text-sm uppercase font-bold"> Seconds </div>
          </div>

        </div>
      </span>
      <span slot="finish">Done!</span>
    </vac>
  </client-only>
</template>
