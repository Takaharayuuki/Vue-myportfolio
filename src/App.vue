<template>
  <div>
    <navheader></navheader>
      <div class='container'>
        <transition>
          <router-view />
        </transition>
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
