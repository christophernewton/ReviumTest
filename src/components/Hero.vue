<template>
    <section class="hero">
      <img :src="image" v-if="image" />
      <h1 class="hero__content">
        <slot name="title" />
      </h1>
      <slot />
    </section>
</template>

<script>
  export default {
    name:'Hero',
    props: {
      image: {
        type:String,
        default:null
      }
    }
  }
</script>

<style lang="scss">
  img {
    height:auto;
    object-fit: cover;
    width:100%;
    height:100%;
    position: absolute;
  }
  .hero {
    min-height:calc(100vh - 83px);
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    &__content {
      color:#fff;
      font-weight:900;
      text-align:center;
      position: relative;
      display: flex;
      position: absolute;
      font-size:72px;
    }
    &__link {
      position: absolute;
      bottom:100px;
      color:#fff;
    }
  }
</style>