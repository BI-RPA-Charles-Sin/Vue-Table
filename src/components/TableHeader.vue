<template>
  <thead class="custom-table-header">
    <th>Index</th>
    <th>Name</th>
  </thead>
</template>

<script>
export default {
  name: "TableHeader",
};
</script>

<style scoped>
.custom-table-header {
  border-radius: 4px;
}

.custom-table-header th {
  border: 1px solid #333333;
}

.custom-table-header th:first-child {
  border-top-left-radius: 4px;
}

.custom-table-header th:last-child {
  border-top-right-radius: 4px;
}

.custom-table-header th:first-child {
  border-right-width: 0px;
}
</style>
