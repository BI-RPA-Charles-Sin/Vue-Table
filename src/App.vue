<template>
  <div class="container">
    <Table :state="state.data" />
  </div>
</template>

<script>
import { reactive } from "vue";
// Component
import Table from "./components/Table";
// Data
import usersData from "./mock/users.json";

export default {
  name: "App",
  components: { Table },

  setup() {
    const state = reactive({
      data: usersData,
    });

    return {
      state,
    };
  },
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
