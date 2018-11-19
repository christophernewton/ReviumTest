<template>
  <div id="app">
    <header-area />
    <hero image="https://via.placeholder.com/1920x1080">
      <div slot="title">WELCOME TO LIFE<br />AT THE PATCH</div>
    </hero>
    <hero>
      <div slot="title">
        WOLLERT'S MAGNETIC<br />
        NEW NEIGHBOUTHOOD.<br />
        WHERE THE DESTINATION<br />
        IS LOVAL.
      </div>
      <a href="" class="hero__link">DISCOVER THE PATCH</a>
    </hero>
  </div>
</template>

<script>
import HeaderArea from '@/components/HeaderArea.vue'
import Hero from '@/components/Hero.vue'
export default {
  name: 'app',
  components: {
    HeaderArea,
    Hero
  }
}
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Lato:400,900');
  html, body {
    background:#000;
    color:#fff;
    font-family: 'Lato', arial;
    font-size:15px;
  }
</style>
