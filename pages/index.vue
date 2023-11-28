<template>
  <div>
    <USPSHeader />
    <AppHeader />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import USPSHeader from '~/components/USPSHeader.vue'
import AppHeader from '~/components/AppHeader.vue';

export default Vue.extend({
  name: 'IndexPage',
  components: { USPSHeader, AppHeader },
})
</script>
