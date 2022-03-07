<template>
  <!-- testimonial section  -->
  <section>
    <div id="testimonials" class="colored-sec">
      <div
        id="carouselExampleControls"
        class="carousel slide"
        data-ride="false"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <h2 class="testimonial-text">
              I no longer have to sniff other dogs for love. I've found the
              hottest Corgi on TinDog. Woof. 
            </h2>
            <img
              class="testimonial-img"
              src="./images/dog-img.jpg"
              alt="dog-profile"
            />
            <em>Pebbles, New York</em>
          </div>
          <div class="carousel-item">
            <h2 class="testimonial-text">
              My dog used to be so lonely, but with TinDog's help, they've found
              the love of their life. I think.
            </h2>
            <img
              class="testimonial-img"
              src="./images/lady-img.jpg"
              alt="lady-profile"
            />
            <em>Beverly, Illinois</em>
          </div>
        </div>
        <a
          class="carousel-control-prev"
          href="#carouselExampleControls"
          role="button"
          data-slide="prev"
        >
          <span class="carousel-control-prev-icon"></span>
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleControls"
          role="button"
          data-slide="next"
        >
          <span class="carousel-control-next-icon"></span>
        </a>
      </div>
    </div>

    <!-- press  -->
    <div id="press" class="colored-sac">
      <img class="press-logo" src="./images/techcrunch.png" alt="tc-logo" />
      <img class="press-logo" src="./images/tnw.png" alt="tnw-logo" />
      <img
        class="press-logo"
        src="./images/bizinsider.png"
        alt="biz-insider-logo"
      />
      <img class="press-logo" src="./images/mashable.png" alt="mashable-logo" />
    </div>
  </section>
</template>

<style scoped>
/* Testimonial Section */

#testimonials {
    
    text-align: center;
    background: #ff4c68;
    color: #fff;
}

.testimonial-img {
    width: 10%;
    border-radius: 100%;
    margin: 20px;
}
/* carousel testimonial */
.carousel-inner {
    padding: 7% 15%;
    margin: auto;
    
}
.carousel-inner h2 {
    font-size: 3rem;
}


/* press section */
#press {
    background:#ff4c68;
    text-align: center;
    padding-bottom: 3%;
}

.press-logo {
    width: 10%;
    margin: 20px 20px 50px;
}


</style>