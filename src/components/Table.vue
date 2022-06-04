<template>
  <table class="custom-table">
    <thead class="custom-table-header">
      <th>Index</th>
      <th>Name</th>
    </thead>
    <tbody class="custom-table-body">
      <tr>
        <td>1</td>
        <td>One</td>
      </tr>
      <tr>
        <td>2</td>
        <td>Two</td>
      </tr>
      <tr>
        <td>3</td>
        <td>Three</td>
      </tr>
      <tr>
        <td>4</td>
        <td>Four</td>
      </tr>
      <tr>
        <td>5</td>
        <td>Five</td>
      </tr>
      <tr>
        <td>6</td>
        <td>Six</td>
      </tr>
      <tr>
        <td>7</td>
        <td>Seven</td>
      </tr>
      <tr>
        <td>8</td>
        <td>Eight</td>
      </tr>
      <tr>
        <td>9</td>
        <td>Nine</td>
      </tr>
      <tr>
        <td>10</td>
        <td>Ten</td>
      </tr>
    </tbody>
  </table>
</template>

<style scoped>
.custom-table {
  border-spacing: 0px;
  border-radius: 4px;
  margin: 20px auto;
  box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
}

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
