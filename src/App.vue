<template>
  <div>
    <the-header></the-header>
    <the-feature></the-feature>
    <the-testimonial></the-testimonial>
    <the-footer></the-footer>
  </div>
</template>

<script>
import TheHeader from "./components/TheHeader.vue";
import TheFeature from "./components/TheFeature.vue";
import TheTestimonial from "./components/TheTestimonial.vue";
import TheFooter from "./components/TheFooter.vue";
export default {
  components: { TheHeader, TheFeature, TheTestimonial, TheFooter },
  data() {},
};
</script>

<style>
body {
  font-family: "Montserrat";
}
.colored-sec {
  background-color: #ff4c68;
  color: #fff;
}

.white-sec {
  background-color: #fff;
}
</style>
