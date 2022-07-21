<template>
  <div class="projects-page">
    <h1>My Projects</h1>
    <div class="projects-container">
      <div class="first-project-box">
        <div class="project-box number-guesser">
          <h4>Number Guesser Game</h4>
          <a href="https://the-number-guesser-game.netlify.app/"> 
            <i class="fas fa-eye"></i> <p class="link">Preview</p> 
          </a>
        </div>
        <div class="project-box tasklist">
          <h4>Tasklist</h4>
          <a href="https://mayana-tasklist.netlify.app/"> 
            <i class="fas fa-eye"></i> <p class="link">Preview</p>
          </a> 
        </div>
        <div class="project-box bookmark last-box">
          <h4>Bookmark</h4>
          <a href="https://mayana-bookmark-app.netlify.app/"> 
            <i class="fas fa-eye"></i> <p class="link">Preview</p> 
          </a>
        </div>
      </div>
      <div class="second-project-box">
        <div class="project-box tracalorie">
          <h4>Tracalorie App</h4>
          <a href="https://tracalorie-meal-calorie-tracker.netlify.app/">
            <i class="fas fa-eye"></i> <p class="link">Preview</p> 
          </a>
        </div>
        <div class="project-box loan-calculator">
          <h4>Loan Calculator</h4>
          <a href="https://mayana-loan-calculator.netlify.app/">
            <i class="fas fa-eye"></i> <p class="link">Preview</p> 
          </a>
        </div>
        <div class="project-box movie-app last-box">
          <h4>Movie App</h4>
          <a href="https://techkid-movie-app.netlify.app/"> 
            <i class="fas fa-eye"></i> <p class="link">Preview</p> 
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    layout: 'projects'
  }
</script>

<style scoped>
  .projects-page {
    color: white;
    text-align: center;
  }

  .projects-page h1 {
    font-size: 2.5rem;
    margin: 1rem 0;
    margin-top: 0;
  }

  .projects-container {
    width: 75%;
    height: 17.5rem;
    margin: 0 auto;
  }

  .first-project-box {
    display: flex;
    justify-content: space-between;
    height: 7.5rem;
  }

  .project-box {
    background: 
      linear-gradient(to right, rgba(29, 29, 29, 0.329), rgba(73, 73, 73, 0.192)), 
      url('~/assets/img/project-1.jpg');
    background-size: cover;
    width: 22.5%;
    height: 6rem;
    border-bottom: 5px solid rgb(56, 61, 61);
    cursor: pointer;
    border-radius: 10px;
    box-shadow: 0px 0px 18px 6px rgb(26, 26, 26);
    transition: 500ms ease-in-out;
  }

  .number-guesser {
    background: 
      linear-gradient(to right, rgba(29, 29, 29, 0.329), rgba(73, 73, 73, 0.192)), 
      url('~/assets/img/number-guesser.png');
  }

  .tasklist {
    background: 
      linear-gradient(to right, rgba(29, 29, 29, 0.329), rgba(73, 73, 73, 0.192)), 
      url('~/assets/img/tasklist.png');
  }

  .bookmark {
    background: 
      linear-gradient(to right, rgba(29, 29, 29, 0.329), rgba(73, 73, 73, 0.192)), 
      url('~/assets/img/bookmark.png');
  }

  .tracalorie {
    background: 
      linear-gradient(to right, rgba(29, 29, 29, 0.329), rgba(73, 73, 73, 0.192)), 
      url('~/assets/img/tracalorie.png');
  }

  .loan-calculator {
    background: 
      linear-gradient(to right, rgba(29, 29, 29, 0.329), rgba(73, 73, 73, 0.192)), 
      url('~/assets/img/loan-calculator.png');
  }

  .movie-app {
    background: 
      linear-gradient(to right, rgba(29, 29, 29, 0.329), rgba(73, 73, 73, 0.192)), 
      url('~/assets/img/movie-app.png');
  }

  .project-box:hover {
    width: 25%;
    height: 7rem;
    transition: 500ms ease-in-out;
  }

  h4 {
    margin-top: 0.5rem;
  }

  a {
    font-size: 1.25rem;
    font-weight: 600;
    text-decoration: none;
    color: rgb(255, 255, 255);
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    z-index: 1;
    align-items: center;
    text-align: center;
    transition: all 0.5s ease-in-out;
  }

  a:hover {
    color: rgb(0, 0, 0);
    transition: all 0.5s ease-in-out;
  }

  .link {
    transition: all 0.5s ease-in-out;
    color: rgb(233, 233, 233);
  }

  .link:hover {
    color: rgb(255, 255, 255);
    font-size: 1.45rem;
    transition: all 0.5s ease-in-out;
  }

  .second-project-box {
    display: flex;
    justify-content: space-between;
    margin-top: 3rem;
  }

  @media (max-width: 768px) {
    .projects-page {
      padding-top: 2rem;
    }

    .projects-container {
      width: 95%;
    }

    .projects-container {
      display: flex;
      justify-content: space-between;
      height: fit-content;
    }

    .first-project-box {
      flex-direction: column;
      justify-content: center;
      align-content: center;
      width: 45%;
      height: fit-content;
    }

    .project-box {
      width: 70%;
      margin: 0 auto;
      margin-bottom: 2rem;
    }

    .project-box:hover {
      width: 75%;
      height: 7rem;
      transition: 500ms ease-in-out;
    }

    .last-box {
      margin-bottom: 0;
    }

    .second-project-box {
      flex-direction: column;
      width: 45%;
      margin: 0;
    }
  }

  @media (max-width: 600px) {
    .projects-container {
      flex-direction: column;
    }

    .first-project-box {
      width: 60%;
      margin: 0 auto;
    }

    .last-box {
      margin-bottom: 2rem;
    }

    .second-project-box {
      width: 60%;
      margin: 0 auto;
    }
  }
</style>