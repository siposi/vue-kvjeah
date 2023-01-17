<template>
  <h1>{{ msg }}</h1>
  <table>
    <tr>
      <th>Name</th>
      <th>Name</th>
      <th>Name</th>
      <th>Name</th>
    </tr>
    <tr>
      <td>Value</td>
    </tr>
  </table>
</template>

<script>
export default {
  name: 'RawRegItem',
  props: {
    msg: String,
  },
};
</script>

<style scoped>
h1 {
  margin: 40px 0 0;
  color: blue;
  background: #eeeeee88;
}
table {
  border: collaps;
  
}
</style>
