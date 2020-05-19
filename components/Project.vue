<template>
  <div class="project">
    <h4>{{ header }}</h4>
    <img src="{{ imageUrl }}" alt />
    <p>{{description}}</p>
    <time>{{ date }}</time>
  </div>
</template>

<script>
export default {
  data() {
    return {
      header: "",
      imageUrl: "",
      description: "",
      date: ""
    };
  }
};
</script>

<style>
</style>