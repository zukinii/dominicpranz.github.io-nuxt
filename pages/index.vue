<template>
  <div>
    <section>
      <h1>Intro</h1>
      <p>A short explanation what this site is about</p>
    </section>
    <section>
      <h2>Bio</h2>
      <p>A few short sentences about me to make me seem more human, but no clichee sentences.</p>
    </section>
    <aside>
      <h2>Page Settings</h2>
      <ul>
        <li>Dark Mode</li>
        <li>Switch Background / Style</li>
        <li>...</li>
      </ul>
    </aside>
    <section>
      <h2>List of previous Projects with Images and a short description</h2>
      <ul>
        <li>A Slider? How to make it not boring?</li>
        <li>Left Right Layout? Seems to boring as well</li>
        <li>A cube you can rotate? Maybe...</li>
      </ul>
    </section>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

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
section {
  @apply h-screen w-full bg-blue-300;
}
</style>
