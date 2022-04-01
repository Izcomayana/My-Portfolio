<template>
  <div class="home-page">
    <h2>Hi, Welcome to my portfolio.</h2>
    <h1>Oluwapelumi</h1>
  </div>
</template>

<style>
  .home-page {
    color: white;
    padding-top: 4rem;
    padding-left: 5rem;
    width: 50%;
  }

  h1 {
    font-size: 5rem;
    margin-top: 2rem;
  }

  h2 {
    width: 70vw;
  }

  @media (max-width: 650px) {
    .home-page {
      padding-left: 3.5rem;
    }

    h1 {
      font-size: 3.75rem;
    }

    h2 {
      font-size: 1rem;
    }
  }
  
  @media (max-width: 460px) {
    .home-page {
      padding-left: 2rem;
    }
    
    h1 {
      font-size: 2.75rem;
    }

    h2 {
      font-size: 0.75rem;
    }
  }

  @media (max-width: 300px) {
    h1 {
      font-size: 2rem;
    }
  }
</style>