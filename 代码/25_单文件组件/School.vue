<template>
  <div class="dome">
    <h1>学校名称{{ name }}</h1>
    <h1>学校地址{{ address }}</h1>
    <button @click="showName">点我显示学校名称</button>
  </div>
</template>
<script>
export default {
  name: "School",
  data() {
    return {
      name: "qzc",
      address: "浙江衢州",
    };
  },
  methods: {
    showName() {
      alert(this.name);
    },
  },
};
</script>
<style>
.dome {
  background-color: hotpink;
}
</style>