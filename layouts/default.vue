<template>
  <div class="cover-container d-flex w-100 h-100 p-3 mx-auto flex-column">
    <navbar></navbar>
    <nuxt/>
  </div>
</template>

<script>
import Navbar from "../components/Navbar";
import Footer from "../components/Footer";

export default {
  components: {
    Navbar,
    Footer
  }
};
</script>

<style>
</style>