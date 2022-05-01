<template>
  <div class="contacts-page">
    <h1>You can reach me via:</h1>

    <div class="contact-list">
        <div class="contact-box contact-email">
          <span class="contacts-head">
            <i class="fas fa-envelop"></i> <h3>Email:</h3> 
            <div class="text-secondary">oluwapelumisotoyinbo@gmail.com</div>
          </span> 
        </div>

        <div class="contact-box contact-phone">
          <span class="contacts-head">
            <i class="fas fa-envelop"></i> <h3>Resume Link:</h3> 
            <div class="text-secondary">
              <a href="https://docs.google.com/document/d/1FpB4iGBT0HjCdzvGCbtzdfSfCcu8itZL6YQVXJiu9lI/edit?usp=sharing" 
              download="CV">Oluwapelumi-CV</a></div>
          </span> 
        </div>

        <div class="contact-box contact-phone">
          <span class="contacts-head">
            <i class="fas fa-envelop"></i> <h3>Mobile No:</h3> 
            <div class="text-secondary">08036567514</div>
          </span> 
        </div>

      </div>
  </div>
</template>

<script>
  export default {
    layout: 'contacts'
  }
</script>

<style scoped>
  .contacts-page {
    color: white;
    text-align: center;
  }

  .contacts-page h1 {
    font-size: 2rem;
    margin-top: 0rem;
  }

  .contact-box {
    margin-bottom: 2rem;
  }

  .contacts-head h3 {
    font-size: 1.5rem;
    margin: 0;
    margin-bottom: 1rem;
  }

  .text-secondary {
    font-size: 1.15rem;
  }

  .text-secondary a {
    text-decoration: none;
    color: rgb(255, 255, 255);
    background: transparent;
    border: 1px solid white;
    border-radius: 10px;
    padding: 5px;
    transition: 500ms ease-in-out;
  }

  .text-secondary a:hover {
    color: rgb(0, 0, 0);
    background-color: rgb(255, 255, 255);
    border: 1px solid rgb(0, 0, 0);
    border-radius: 10px;
    transition: 500ms ease-in-out;
  }

  @media (max-width: 600px) {
    .contacts-page h1 {
      font-size: 1.75rem
    }

    h3 {
      font-size: 1.25rem;
    }

    .text-secondary {
      font-size: 1rem;
    }
  }
</style>