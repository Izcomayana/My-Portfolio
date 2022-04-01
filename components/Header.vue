<template>
  <div>
    <header>
      <ul class="header-ul">
        <li><nuxt-link class="nuxt-link" to="/">HOME</nuxt-link></li>
        <li><nuxt-link class="nuxt-link" to="/about">ABOUT ME</nuxt-link></li>
        <li><nuxt-link class="nuxt-link" to="/projects">PROJECTS</nuxt-link></li>
        <li><nuxt-link class="nuxt-link" to="/contacts">CONTATCS</nuxt-link></li>
      </ul>
    </header>
  </div>
</template>

<style scoped>
  header {
    color: white;
    width: 99.7%;
    left: 2rem;
    text-align: center;
  }

  header ul {
    display: flex;
    justify-content: space-between;
    width: 50%;
    height: 2rem;
    margin: 0 auto;
    padding-top: 1rem;
    text-decoration: none;
    list-style: none;
    font-size: 1rem;
  }

  li {
    height: 1.5rem;
    cursor: pointer;
  }

  .nuxt-link {
    border-bottom: 2px solid transparent;
    text-decoration: none;
    color: white;
    padding-bottom: 0.75rem;
    transition: 400ms ease-out;
  }

  .nuxt-link:hover {
    border-bottom: 1px solid white;
    transition: 400ms ease-in;
  }
</style>