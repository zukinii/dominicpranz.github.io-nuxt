<template>
  <div class="section-wrapper">
    <section class="intro">
      <div class="intro-card">
        <h1>Intro</h1>
        <p>A short explanation what this site is about + Contact</p>
        <Projects />
      </div>
    </section>
    <section class="bio">
      <h2>Bio</h2>
      <p>A few short sentences about me to make me seem more human, but no clichee sentences.</p>
    </section>
    <section class="projects">
      <h2>List of previous Projects with Images and a short description and a date</h2>
      <ul>
        <li>A Slider? How to make it not boring?</li>
        <li>Left Right Layout? Seems to boring as well</li>
        <li>A cube you can rotate? Maybe...</li>
      </ul>
    </section>
    <footer>Footer</footer>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Projects from "~/components/Projects.vue";

export default Vue.extend({
  components: {}
});
</script>

<style lang="scss">
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

.section-wrapper {
  //scroll-snap-type: y proximity;
  height: 100vh;
  overflow-y: scroll;
}

section {
  @apply h-screen w-full bg-blue-300;
  scroll-snap-align: start;
  position: relative;
}

.intro-card {
  background-color: white;
  height: 80%;
  width: 80%;
}

footer {
  scroll-snap-align: end;
  height: 10rem;
}
</style>
