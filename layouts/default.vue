<template>
  <div class="home-layout">
    <Header class="header" />
    <Hamburger />
    <Nuxt />
  </div>
</template>

<script>
  import Hamburger from '../components/Hamburger';
  import Header from '../components/Header';

  export default {
    components: {
      Header,
      Hamburger
    }
  }
</script>

<style >
  .home-layout {
    background: url('~/assets/img/bckgd-2.jpg');
    background-size: cover;
    height: 100vh;
    color: white;
    padding-top: 1px;
  }

  @media (max-width: 768px) {
    .header {
      display: none;
      width: 75%;
    } 

    .mobile header {
      width: 97%;
      height: 98vh;
    }

    .mobile header ul {
      flex-direction: column;
      justify-content: initial;
      width: 96%;
      height: 97vh;
      margin: 0;
      padding: 0;
      padding-top: 1rem;
    }

    .mobile header ul li {
      margin-bottom: 2.5rem;
      font-size: 1.25rem;
    }
  }
</style>