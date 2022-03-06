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
              <a class="nav-link" href="#pricing">Pricing</a>
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
          <img class="title-img" src="images/iphone6.png" alt="iphone-mockup" />
        </div>
      </div>
    </div>
  </section>
</template>
