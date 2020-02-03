<template>
  <div>
    <img src="~/assets/images/sample.jpg">
  </div>
</template>

<script>
</script>

<style>
  h1 {
    text-align: center;
    position: relative;
    top: 280px;
  }
  img {
    width: 100%;
  }
  .fade-enter-active,.fade-leave-active {
    transition: opacity .3s;
  }
  .fade-enter {
    opacity: 0;
  }
  .fade-enter-to {
    opacity: 1;
  }
</style>
