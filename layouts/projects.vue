<template>
  <div class="projects-layout">
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
  .projects-layout {
    font-family: 'Open Sans', sans-serif;
    background: 
      linear-gradient(to right, rgba(39, 39, 39, 0.35), rgba(94, 94, 94, 0.192)), 
      url('~/assets/img/project-2.jpg') center top;
    background-size: cover;
    height: 100vh;
    padding-bottom: 2rem;
  }

  @media (max-width: 768px ) {
    .projects-layout {
      height: 100vh;
    }
    
    header ul {
      flex-direction: row;
    }
  }

  @media (max-width: 750px) {
    .projects-layout {
      height: 100%;
    }
  }
</style>