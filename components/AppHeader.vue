<!-- Please remove this file from your project -->
<template>
  <div
    class="w-full h-24 px-[127px] py-[30px] bg-white justify-between items-center inline-flex"
  >
    <img
      class="w-48 h-9"
      alt="Clarifion Logo"
      src="~/assets/ClarifionLogoHeader.png"
    />
    <div class="justify-start items-start gap-8 flex">
      <img
        alt="McAfee Logo"
        src="~/assets/McAfeeLogopngHeader.png"
        class="w-[82px] h-8 relative"
      />
      <img
        alt="Norton Logo"
        src="~/assets/NortonLogoHeader.png"
        class="w-[82px] h-8 relative"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
  components: {},
}
</script>

<style module>
.HeaderContainer {
  background-color: red;
}

.HeaderLogo {
}
</style>
