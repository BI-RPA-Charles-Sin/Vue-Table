<template>
  <tbody class="custom-table-body">
    <tr v-for="item in data" :key="item.id">
      <td>{{ item.id }}</td>
      <td>{{ item.name }}</td>
    </tr>
  </tbody>
</template>

<script>
export default {
  name: "TableContent",
  props: {
    data: Array,
  },
};
</script>

<style scoped>
.custom-table-body {
  border-radius: 4px;
}

.custom-table-body td {
  border-bottom: 1px solid #333333;
  border-left: 1px solid #333333;
  border-right: 1px solid #333333;
}

.custom-table-body td:first-child {
  border-right-width: 0px;
}

.custom-table-body tr:last-child td:first-child {
  border-bottom-left-radius: 4px;
}

.custom-table-body tr:last-child td:last-child {
  border-bottom-right-radius: 4px;
}
</style>
