<template>
  <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
    <ul>
      <li>
        <a class="navbar-brand" href="#">Home</a>
      </li>
      <li>
        <a class="navbar-brand" href="#">About</a>
      </li>
      <li>
        <a class="navbar-brand" href="#">Contact</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "navbar",
  data() {
    return {};
  }
};
</script>

<style scoped>
nav ul {
  list-style-type: none;
}

li {
  display: inline-block;
  list-style-type: none;
  margin: 0 10px;
}
</style>
