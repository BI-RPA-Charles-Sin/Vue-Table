<template>
  <div class="container">
    <Table />
  </div>
</template>

<script>
import Table from "./components/Table";

export default {
  name: "App",
  components: { Table },
};
</script>

<style>
body {
  padding: 0;
  margin: 0;
  height: 100vh;
  width: 100vw;
}

.container {
  margin: 0 auto;
  width: 100%;
  height: 100%;
}
</style>
