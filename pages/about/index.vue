<template>
  <div class="about-page">
    <h1>About Me</h1>
    <div class="about-paragraph">
      <p>
        <span> <h2>My Name is Sotoyinbo Oluwapelumi.</h2> </span>
        A creative individual with knowledge using Modern productivity tools, 
        user friendly and good communication skills and quality web platforms. 
        My strength lies within HTML, CSS, SCSS, Javascript, VueJs, and Nuxt. 
        I craft high-performance web products using my stack and I am dedicated to learning, 
        evaluating, and applying new technologies to enhance content and functionality.   
      </p>
      <p>
        <span> <h2>My Transition Into Tech</h2> </span>
        I was 16 years old when I first heard about Frontend Development from a Friend. 
        I didn't really know much so I made a lot of research on it and I really loved it, 
        Got to know much better about it 2019 and I started learning January 2020.
      </p>
      <p>
        <span> <h2>And The Jouney Began...</h2> </span> 
        I started well cause I was motivated and willing to learn,
        It was pretty easy at the begining when I started with HTML & CSS and I finished both within two weeks. 
        I had some issues though but it wasn't really hard or impossible for me to solve,
        and I had some help too soo I can say it was kinda easy.
      </p>
      <p>
        <span> <h2>Into the wicked world of JavaScript</h2> </span>
        Hmn...JavaScript really taught me a lot about coding. Aside from the code aspect of it, 
        It improved my problem solving skills, functionalty and opened my eyes to the more side of Frontend Engineering.
        JavaScript made me realise there's always more to do aside from the interface. 
        It was hard at first and the frustration from my issues with some of my 
        JavaScript projects made me want to quit but because of my passion for it 
        and with the help of some good people I didn't give up. 
        After a month I was really glad I finished JavaScript!
      </p>
      <p>
        <span> <h2>JavaScript frameworks</h2> </span> 
        After finishing some JavaScript projects I started learning VueJs. 
        VueJs made JavaScript easier and Nuxt made Vue easier for me. 
        I'm still gonna be learning some more JavaScript frameworks like React... 
        but I want to be very good with the ones I know first.
        Employing the use of the Vue JavaScript framework and a collection of CSS frameworks, 
        I have optimized their strengths to be a more efficient developer while still 
        maintaining a solid knowledge of the basics.
      </p>
      <p>
        As a frontend developer, I am aware that I will be part of a development team. 
        That is why it is of essence to me to know how to use the most software development tools.
        I really wish my code would never have bugs, but that's just a wish. 
        That's why the ability to test and debug is another important technical skill I possess.
        As a frontend developer, I am responsible for how websites and applications look, 
        so I am challenged to be creative and come up with new solutions to the most common user interface problems.
      </p>
    </div>
  </div>
</template>

<script>
  export default {
    layout: 'about'
  }
</script>

<style scoped>
  .about-page {
    color: rgb(255, 255, 255);
    text-align: center;
    padding-bottom: 2rem;
  }

  .about-page h1 {
    font-size: 2.5rem;
    margin: 0rem;
    padding-top: 0.5rem;
  }

  .about-paragraph {
    width: 75%;
    margin: 0 auto;
  }

  p {
    padding: 0.25rem;
    font-size: 1rem;
    line-height: 1.5rem;
  }

  h2 {
    margin: 0.5rem auto;
    font-size: 1.25rem;
    font-weight: 900;
  }

  @media (max-width: 768px) {
    .about-paragraph {
      width: 95%;
    }

    p {
      padding: 0;
      font-size: 1.25rem;
      line-height: 1.75rem;
    }
  }

  @media (max-width: 600px) {
    .about-page h1 {
      font-size: 2rem;
      padding-top: 4rem; 
      margin: 0;
      margin-bottom: 0.25rem;
    }
    
    p {
      padding: 0;
      font-size: 1rem;
      line-height: 1.5rem;
    }
  }
</style>