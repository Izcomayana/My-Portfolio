<template>
  <div>
    <MobileNav v-if="!showMobileNav" />
    <div class="hamburger-container" >
      <div class="hamburger" :class="{ 'open': !showMobileNav }" @click="showMobileNav = !showMobileNav" ></div>
    </div>
  </div>
</template> 

<script>
  import MobileNav from '../components/MobileNav';

  export default {
    components: {
      MobileNav
    },
    data () {
      return {
        showMobileNav: true,
      }
    }
  }
</script>

<style scoped>
  .hamburger-container {
    display: none;
  }

  @media (max-width: 768px) {
    .hamburger-container {
      display: block;
      position: absolute;
      z-index: 1;
      top: 1rem;
      right: 1rem;
      height: 25px;
      width: 35px;
      cursor: pointer;
    }

    .hamburger {
      position: absolute;
      right: 0;
      top: 0.5rem;
      width: 30px;
      height: 3px;
      background: rgb(255, 255, 255);
      transition: 500ms ease-in-out;
      display: block;
    }

    .hamburger::before {
      content: "";
      position: absolute;
      left: 0;
      top: -8px;
      width: 30px;
      height: 3px;
      background: rgb(255, 255, 255);
      transition: 500ms ease-in-out;
    }

    .hamburger::after {
      content: "";
      position: absolute;
      left: 0;
      top: 8px;
      width: 30px;
      height: 3px;
      background: rgb(255, 255, 255);
      transition: 500ms ease
    }

    .open {
      transform: rotate(360deg);
      background: transparent;
      transition: 500ms ease-in-out;
    }

    .open::before {
      transform: rotate(45deg) translate(5px, 8px);
      transition: 500ms ease-in-out;
    }

    .open::after {
      width: 30px;
      transform: rotate(-45deg) translate(3px, -7px);
      transition: 500ms ease-in-out;
    }

  }
</style>