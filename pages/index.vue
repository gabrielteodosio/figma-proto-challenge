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

    <AppFooter />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

import AppHeader from '~/components/AppHeader.vue'
import AppFooter from '~/components/AppFooter.vue'
import USPSHeader from '~/components/USPSHeader.vue'
import StepperComponent from '~/components/StepperComponent.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: { USPSHeader, AppHeader, StepperComponent, AppFooter },
})
</script>
