<template>
  <div>
    <h1>学生姓名{{ name }}</h1>
    <h1>年龄{{ age }}</h1>
  </div>
</template>

<script>
export default {
  name: "Student",
  data() {
    return {
      name: "张三",
      age: 18,
    };
  },
};
</script>

<style>
</style>