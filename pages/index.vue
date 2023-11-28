<template>
  <div>
    <USPSHeader />
    <AppHeader />

    <h1
      class="text-black text-5xl font-['Manrope'] capitalize leading-[48px] text-center"
    >
      Wait ! your order in progress.
    </h1>
    <h2
      class="text-neutral-600 text-2xl font-['Manrope'] capitalize leading-normal text-center"
    >
      Lorem ipsum dolor sit amet, consectetur adipiscing
    </h2>

    <StepperComponent />

    <div class="mx-[127px] p-[40px] my-[40px] bg-neutral-50 rounded-[10px]">
      <div>
        <img
          src="~/assets/image4.png"
          alt="Product image to be sold"
          class="w-[575px] h-[591px] rounded-[10px]"
        />

        <div class="w-[575px] p-6 mt-6 bg-white rounded-[10px] flex-col">
          <div class="flex items-center">
            <img
              src="~/assets/GirlImage.png"
              class="w-12 h-12 mr-3 rounded-[100px]"
              alt="Rounded image of a female costumer"
            />

            <div>
              <div class="flex mb-[8.35px]">
                <GoldenStarIcon />
                <GoldenStarIcon />
                <GoldenStarIcon />
                <GoldenStarIcon />
                <GoldenStarIcon />
              </div>
              <div class="flex justify-center">
                <span
                  class="text-zinc-800 text-sm font-bold font-['Manrope'] leading-[14px]"
                >
                  Ken T.
                </span>
                <VerifyIcon class="mx-1" />
                <span
                  class="text-emerald-400 text-xs font-normal font-['Manrope'] leading-[14.40px]"
                >
                  Verified Customer
                </span>
              </div>
            </div>
          </div>
          <p
            class="text-neutral-600 text-base font-normal font-['Manrope'] leading-normal"
          >
            “As soon as the Clarifions arrived I put one in my bedroom. This was
            late in the afternoon. When I went to the bedroom in the evening it
            smelled clean. When I went to bed I felt I could breathe better.
            Wonderful.”
          </p>
        </div>
      </div>
      <div></div>
    </div>

    <AppFooter />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

import AppHeader from '~/components/AppHeader.vue'
import AppFooter from '~/components/AppFooter.vue'
import USPSHeader from '~/components/USPSHeader.vue'
import StepperComponent from '~/components/StepperComponent.vue'

import VerifyIcon from '~/components/icons/VerifyIcon.vue'
import GoldenStarIcon from '~/components/icons/GoldenStarIcon.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: {
    USPSHeader,
    AppHeader,
    StepperComponent,
    AppFooter,
    VerifyIcon,
    GoldenStarIcon,
  },
})
</script>
