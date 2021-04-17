<template>
  <div>
    <Navbar />

    <div class="container">
      <router-view />
    </div>
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
export default {
  /*eslint-disable*/
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<style></style>
