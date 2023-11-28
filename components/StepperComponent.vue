<template>
  <div class="w-full flex justify-center">
    <div
      class="mx-[7.75rem] w-full h-10 mt-[3.75rem] justify-between items-center inline-flex"
    >
      <div class="justify-start items-center gap-5 flex">
        <div
          class="w-10 h-10 justify-center items-center flex bg-lime-400 rounded-full border-2 border-lime-400"
        >
          <Icon icon="charm:tick" class="w-7 h-7" color="white" />
        </div>
        <div
          class="text-black text-xl font-normal font-['Manrope'] capitalize leading-snug"
        >
          Step 1 : Cart Review
        </div>
      </div>
      <div class="justify-start items-center gap-5 flex">
        <div
          class="w-10 h-10 bg-lime-400 justify-center items-center flex rounded-full border-2 border-lime-400"
        >
          <Icon icon="charm:tick" class="w-7 h-7" color="white" />
        </div>
        <div
          class="text-black text-xl font-normal font-['Manrope'] capitalize leading-snug"
        >
          Step 2 : Checkout
        </div>
      </div>
      <div class="justify-start items-center gap-5 flex">
        <div
          class="w-10 h-10 bg-blue-500 flex items-center justify-center rounded-full border-2 border-blue-500"
        >
          <div
            class="text-white text-xl font-normal font-['Manrope'] capitalize leading-snug"
          >
            3
          </div>
        </div>
        <div
          class="text-black text-xl font-bold font-['Manrope'] capitalize leading-snug"
        >
          Step 3 : Special Offer
        </div>
      </div>
      <div class="justify-start items-center gap-5 flex">
        <div
          class="w-10 h-10 flex items-center justify-center rounded-full border-2 border-blue-500"
        >
          <span
            class="text-blue-500 text-xl font-normal font-['Manrope'] capitalize leading-snug"
          >
            4
          </span>
        </div>
        <div
          class="text-black text-xl font-normal font-['Manrope'] capitalize leading-snug"
        >
          Step 4 : Confirmation
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Icon } from '@iconify/vue2'

export default {
  name: 'StepperComponent',
  components: {
    Icon,
  },
}
</script>
