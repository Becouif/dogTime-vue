<template>
  <!-- Call to Action -->

  <section id="cta" class="colored-sec">
    <h3 class="cta-font-size col-8">
      Find the True Love of Your Dog's Life Today.
    </h3>
    <button type="button" class="btn btn-lg btn-dark download-btn dl-btn">
      <i class="fab fa-apple"></i> Download
    </button>
    <button
      type="button"
      class="btn btn-lg btn-outline-light download-btn dl-btn"
    >
      <i class="fab fa-google-play"></i> Download
    </button>
  </section>

  <!-- Footer -->

  <footer id="footer" class="white-sec">
    <div class="foot-icon-cont">
      <i class="fab fa-twitter foot-icon"></i>
      <i class="fab fa-facebook-f foot-icon"></i>
      <i class="fab fa-instagram foot-icon"></i>
      <i class="fas fa-envelope foot-icon"></i>
    </div>
    <p>© Copyright 2018 TinDog.</p>
  </footer>
</template>

<style scoped>
/* call to action */
#cta {
  text-align: center;
  background: #ff4c68;
  padding: 7% 25%;
  color: #fff;
}
#cta h3 {
  font-family: "Montserrat-Black", sans-serif;
  font-size: 3rem;
  margin: auto;
  font-weight: 600;
  line-height: 1.5;
}

/* footer section */
#footer {
  text-align: center;
  padding: 5% 10%;
}
.fa_foot {
  margin: 10px 10px;
}
.copyright_footer {
  margin-top: 20px;
}
</style>
