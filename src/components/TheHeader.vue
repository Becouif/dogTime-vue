<template>
  <section id="title" class="colored-sec">
    <div class="container-fluid">
      <!-- Nav Bar -->

      <nav class="navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="">tindog.</a>

        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#footer">Contact</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#cta">Download</a>
            </li>
          </ul>
        </div>
      </nav>

      <!-- Title -->
      <div class="row">
        <div class="col">
          <h1 class="big-heading">Meet new and interesting dogs nearby.</h1>
          <button type="button" class="btn btn-dark btn-lg download-btn">
            <i class="fab fa-apple"></i> Download
          </button>
          <button
            type="button"
            class="btn btn-outline-light btn-lg download-btn"
          >
            <i class="fab fa-google-play"></i> Download
          </button>
        </div>
        <div class="col-lg-6">
          <img
            class="title-img"
            src="./images/iphone6.png"
            alt="iphone-mockup"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* title section */

#title {
  background: #ff4c68;
  color: white;
  padding-bottom: 60px;
}

div.container-fluid {
  padding: 3% 15%;
}

.btn {
  margin: 10px;
}

/* navigation bar */
h1.h1 {
  font-family: "Montserrat", sans-serif;
  font-weight: 900;
  font-size: 3.5rem;
  line-height: 1.5;
}
nav.navbar {
  padding-bottom: 4.5rem;
}

a.navbar-brand {
  font-family: "ubuntu";
  font-size: 2.5rem;
  font-weight: bolder;
}
.nav-item {
  padding: 0 18px;
}

.nav-link {
  font-size: 1.2rem;
  font-family: "Montserrat-light";
}

/* nav download-button */

button.download-button {
  margin: 5% 3% 5% 0;
  padding: 10px;
  font-family: "Montserrat", sans-serif;
}

/* Title Image */
.title-img {
  width: 60%;
  transform: rotate(25deg);
  position: absolute;
  right: 30%;
}

/* media query */
@media (max-width: 1080px) {
  .title-img {
    position: static;
    transform: rotate(0);
    width: 40%;
  }
  #title {
    text-align: center;
  }
}
</style>
