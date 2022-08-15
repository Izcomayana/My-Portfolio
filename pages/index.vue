<template>
  <transition name="fade">
    <div class="home-page">
      <h3>Hi, Welcome to my portfolio</h3>
      <h2 class="data-text" data-text="Oluwapelumi">Oluwapelumi</h2>
    <h4 class="job">A Frontend Developer</h4>
    </div>
  </transition>
</template>

<style>
  .data-text {
    position: relative;
    font-size: 9vw;
    -webkit-text-stroke: 0.3vw transparent;
    text-transform: uppercase;
    color: #141414;
  }

  .data-text::before {
    content: attr(data-text);
    position: absolute;
    top: 0;
    width: 0;
    left: 0;
    height: 100%;
    color: #ffffff;
    -webkit-text-stroke: 0vw #383d52;
    border-right: 2px solid #000000;
    overflow: hidden;
    animation: animate 6s linear infinite;
  }

  @keyframes animate {
    0%, 100% {
      width: 0;
    }
    70%,90% {
      width: 90%;
    }
  }

  .home-page {
    color: white;
    padding-top: 4rem;
    padding-left: 5rem;
    /* width: 100%; */
  }


  h1 {
    font-size: 4rem;
    margin-top: 2rem;
  }

  h2 {
    width: 70vw;
    margin: 2rem 0;
  }

  .job {
    display: flex;
    justify-content: flex-end;
    align-content: flex-end;
    width: 99%;
  }

  @media (max-width: 650px) {
    .home-page {
      padding-left: 3.5rem;
    }

    h1 {
      font-size: 3.75rem;
    }
  }
  
  @media (max-width: 460px) {
    .home-page {
      padding-left: 2rem;
    }
    
    h1 {
      font-size: 2.75rem;
    }
  }

  @media (max-width: 300px) {
    h1 {
      font-size: 2rem;
    }
  }
</style>