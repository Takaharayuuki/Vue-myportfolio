<template>
  <div>
    <navheader></navheader>
      <div class='container'>
        <router-view />
      </div>
      <navfooter></navfooter>
  </div>
</template>

<script>
import navheader from '@/components/NavHeader.vue'
import navfooter from '@/components/NavFooter.vue'

export default {
  name: "App",

  components: {
    navheader,
    navfooter
  },

  data: () => ({
    //
  })
};
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;600;700&display=swap');
</style>