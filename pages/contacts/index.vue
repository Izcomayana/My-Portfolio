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
            <i class="fas fa-envelop"></i> <h3>Mobile No:</h3> 
            <div class="text-secondary">08036567514</div>
          </span> 
        </div>

        <div class="contact-box contact-address">
          <span class="contacts-head">
            <i class="fas fa-envelop"></i> <h3>Address:</h3>
            <div class="text-secondary">123 First <Small>t. Houston, Texas</Small></div>
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