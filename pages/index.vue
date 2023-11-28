<template>
  <USPSHeader />
</template>

<script lang="ts">
import Vue from 'vue'
import USPSHeader from '~/components/USPSHeader.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: { USPSHeader },
  head() {
    return {
      title: 'Challenge - Figma Prototype'
    }
  },
})
</script>
