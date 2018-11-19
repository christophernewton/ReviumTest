<template>
    <div class="container">
      <header>
        <nav class="row nav">
          <a href="" class="col-lg nav__link">DISCOVER THE PATCH</a>
          <a href="" class="col-lg nav__link">NOW SELLING</a>
          <a href="" class="col-lg nav__link">MASTERPLAN</a>
          <a href="" class="col-lg nav__logo">THE PATCH</a>
          <a href="" class="col-lg nav__link">NEWS &amp; UPDATES</a>
          <a href="" class="col-lg nav__link">MY PATCH</a>
          <a href="" class="col-lg nav__link--register">REGISTER NOW</a>
        </nav>
      </header>
    </div>
</template>

<script>
    export default {
        name:'HeaderArea'
    }
</script>

<style lang="scss" scoped>
  $link-color:#fff;
  .nav {
    align-items: center;
    justify-content: space-evenly;
    &__link,
    &__link--register {
      color:$link-color;
      font-size:13px;
      text-align:center;
      white-space: nowrap;
      margin-top:23px;
      margin-bottom:23px;
      padding-top:8px;
      padding-bottom:8px;
    }
    &__link--register {
      border: 1px solid #fff;
    }
    &__logo {
      color:#000;
      background:#fff;
      text-align: center;
    }
  }
</style>