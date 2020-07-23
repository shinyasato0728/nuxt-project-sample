<template>
  <main>
    <Header />
    <p class="layout-paragraph">共通のLayoutです。この部分はページを切り替えてもデザインが変わりません。</p>
    <Nuxt />
  </main>
</template>

<style>
  body {
    background: #f8f8f9;
  }
  main {
    text-align: center;
  }
  .layout-paragraph {
    background: lightskyblue;
  }
</style>

<script>
import Header from '../components/Header.vue'

export default {
  components: {
    Header
  }
}
</script>