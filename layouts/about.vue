<template>
  <div class="about-container">
    <div class="about-layout">
      <Header class="header" />
      <Hamburger />
      <Nuxt />
    </div>
  </div>
</template>

<style scoped>
  .about-layout {
    background: 
    linear-gradient(to right, rgba(39, 39, 39, 0.178), rgba(0, 0, 0, 0.712)), 
                      url('~/assets/img/project-6.jpg') center top;
    background-repeat: no-repeat;
    background-size: cover;
    text-align: center;
    font-family: 'Open Sans', sans-serif;
  }
  
  .about-layout .header-component {
    color: black;
    position: fixed;
  }
</style>