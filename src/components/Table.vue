<template>
  <table class="custom-table">
    <TableHeader />
    <TableContent />
  </table>
</template>

<script>
import TableHeader from "./TableHeader";
import TableContent from "./TableContent";

export default {
  name: "Table",
  components: { TableHeader, TableContent },
};
</script>

<style scoped>
.custom-table {
  border-spacing: 0px;
  border-radius: 4px;
  margin: 20px auto;
  box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
}
</style>
