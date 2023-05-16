<template>
  <div class="info">
    <h2>姓名：{{ name }}</h2>
    <h2>年龄：{{ age }}</h2>
    <h2>身高：{{ height }}</h2>
  </div>
</template>

<script>
export default {
  // 作用：接收父组件传递过来的属性
  props: ["name", "age", "height"],
  //   data() {
  //     return {};
  //   },
};
</script>

<style scoped></style>
