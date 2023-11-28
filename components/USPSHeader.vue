<!-- Please remove this file from your project -->
<template>
  <div :class="[$style.usps]">
    <div>
      <USPSCheckmarkIcon />
      <span :class="[$style.uspsText]">30-DAY SATISFACTION GUARANTEE</span>
    </div>
    <div>
      <USPSTruckIcon />
      <span :class="[$style.uspsText]">
        Free delivery on orders over $40.00
      </span>
    </div>
    <div>
      <USPSHeartIcon />
      <span :class="[$style.uspsText]">50.000+ HAPPY CUSTOMERS</span>
    </div>
    <div>
      <USPSArrowSyncIcon />
      <span :class="[$style.uspsText]">100% Money Back Guarantee</span>
    </div>
  </div>
</template>

<script>
import USPSHeartIcon from './Icons/USPSHeartIcon.vue'
import USPSTruckIcon from './Icons/USPSTruckIcon.vue'
import USPSArrowSyncIcon from './Icons/USPSArrowSyncIcon.vue'
import USPSCheckmarkIcon from './Icons/USPSCheckmarkIcon.vue'

export default {
  name: 'USPSHeader',
  components: {
    USPSHeartIcon,
    USPSTruckIcon,
    USPSCheckmarkIcon,
    USPSArrowSyncIcon,
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
}

.uspsText {
  font-family: 'Manrope', Arial, Helvetica, sans-serif;

  color: #ffffff;
  text-transform: uppercase;
  font-size: 12pt;
}
</style>
