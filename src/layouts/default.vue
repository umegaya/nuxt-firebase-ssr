<template>
  <div class="wrap">
    <Header />
    <transition name="fade">
      <nuxt />
    </transition>
  </div>
</template>

<script>
import Header from '~/components/Header'

export default {
  components: { Header }
}
</script>

<style>
body {
  background: #f0f0f0;
}
.fade-enter-active, .fade-leave-active {
  transition: all .5s;
}

.fade-enter, .fade-leave-active {
  opacity: 0;
}
</style>

