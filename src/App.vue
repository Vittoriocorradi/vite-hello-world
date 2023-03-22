<script setup>
  import AppTitle from './components/AppTitle.vue';
  import AppParagraph from './components/AppParagraph.vue';
  import AppHero from './components/AppHero.vue';
</script>

<template>
  <div class="container">
    <AppTitle></AppTitle>
    <AppParagraph></AppParagraph>
    <AppHero></AppHero>
  </div>
</template>

<style scoped>
  .container {
    max-width: 71.25rem;
    margin: 0 auto;
    background-color: #1b2838;
    padding: 6.25rem 3.125rem 3.125rem;
    border-radius: 1.875rem;
  }
</style>
