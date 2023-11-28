<!-- Please remove this file from your project -->
<template>
  <div
    class="mt-[61px] w-full h-88 px-[7.75rem] py-6 bg-slate-800 justify-between items-center gap-[592px] inline-flex"
  >
    <div
      class="self-stretch py-2 rounded justify-start items-center gap-4 inline-flex"
    >
      <div
        class="text-white text-base font-normal font-['Manrope'] capitalize leading-snug"
      >
        Copyright (c) 2023
      </div>
      <hr class="w-6 h-[0px] rotate-90 border border-white" />
      <div
        class="text-white text-base font-normal font-['Manrope'] lowercase leading-snug"
      >
        Clarifionsupport@clarifion.com
      </div>
    </div>
    <div class="self-stretch justify-start items-center gap-4 inline-flex">
      <Icon icon="teenyicons:lock-outline" color="white" class="w-4 h-4" />
      <span
        class="text-center text-white text-base font-normal font-['Manrope'] capitalize leading-normal"
      >
        Secure 256-bit SSL encryption.
      </span>
    </div>
  </div>
</template>

<script>
import { Icon } from '@iconify/vue2';

export default {
  name: 'AppFooter',
  components: { Icon },
}
</script>
