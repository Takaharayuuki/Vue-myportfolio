<template>
  <footer>
    <nav class="footer-nav">
      <ul class="footer-nav__list">
        <li class="footer-nav__item"><router-link to="/">Home<font-awesome-icon icon="home"/></router-link>|</li>
        <li class="footer-nav__item"><router-link to="/about">About</router-link> |</li>
        <li class="footer-nav__item"><router-link to="/works">Works</router-link> |</li>
        <li>
          <router-link to="/contact">Contact</router-link>
        </li>
      </ul>
    </nav>
    <div class="sns-link">
      <a href="">
        <font-awesome-icon :icon="['fab', 'twitter']" />
      </a>
      <a href="">
        <font-awesome-icon :icon="['fab', 'github']" />
      </a>
    </div>
    <p class="footer-copyright">
      <small lang="en">&copy;2020 Takaharayuuki</small>
    </p>
  </footer>
</template>

<script>
export default {
  name: "NavFooter"
};
</script>

<style lang="scss">
.footer-nav {

  &__list {
    display:flex;
    list-style: none;
  }
}
</style>