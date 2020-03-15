<template>
  <header class="header">
    <g-link to="/"><h1>👨‍💻 {{siteName}}</h1></g-link>
  </header>
</template>

<script>
export default {
  props: ["siteName"]
};
</script>

<style>
  .header a{
    color:black;
  }
</style>
