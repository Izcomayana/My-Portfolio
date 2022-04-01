<template>
  <div class="contacts-layout">
    <Header class="header" />
    <Hamburger />
    <Nuxt />
  </div>
</template>

<script>
  import Header from '../components/Header';

  export default {
    components: {
      Header
    }
  }
</script>

<style scoped>
  .contacts-layout {
    background: 
      linear-gradient(to right, rgba(39, 39, 39, 0.37), rgba(0, 0, 0, 0.568)), 
        url('~/assets/img/IMG-20201227-WA0003.jpg') center top;
    background-color: black;
    background-repeat: no-repeat;
    background-size: cover;
    background-position-x: center;
    height: 100vh;
    text-align: center;
    padding-top: 1px;
  }
</style>