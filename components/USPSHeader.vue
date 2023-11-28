<!-- Please remove this file from your project -->
<template>
  <div :class="[$style.usps]">
    <div>
      <Icon icon="fluent:checkmark-starburst-20-regular" />
      <span :class="[$style.uspsText]">30-DAY SATISFACTION GUARANTEE</span>
    </div>
    <div>
      <Icon icon="ph:truck-light" />
      <span :class="[$style.uspsText]">
        Free delivery on orders over $40.00
      </span>
    </div>
    <div>
      <Icon icon="mdi:cards-heart-outline" />
      <span :class="[$style.uspsText]">50.000+ HAPPY CUSTOMERS</span>
    </div>
    <div>
      <Icon icon="fluent:arrow-sync-checkmark-20-regular" />
      <span :class="[$style.uspsText]">100% Money Back Guarantee</span>
    </div>
  </div>
</template>

<script>
import { Icon } from '@iconify/vue2'

export default {
  name: 'USPSHeader',
  components: {
    Icon,
  },
}
</script>

<style module>
.usps {
  background-color: #252f3d;
  width: 100vw;
  height: 50px;
  min-height: 50px;

  display: flex;
  flex-direction: row;
  align-items: center;
}

.usps > div {
  flex: 1;
  display: flex;
  justify-content: center;
}

.usps > div > svg {
  margin-right: 8px;
  color: white;
  width: 22px;
  height: 22px;
}

.uspsText {
  font-family: 'Manrope', Arial, Helvetica, sans-serif;

  color: #ffffff;
  text-transform: uppercase;
  font-size: 12pt;
}
</style>
