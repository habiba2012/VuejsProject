<template>
  <div id="app">
    <Navbar />
    <Footer />
    <Middlesection />
  </div>
</template>

<script>
import Navbar from "./Navbar";
import Footer from "./Footer";
import Middlesection from "./Middlesection";

export default {
  name: "app",
  components: {
    Navbar,
    Footer,
    Middlesection
  },
  data() {
    return {
      title: "First Cli project"
    };
  }
};
</script>

<style scoped>
</style>
