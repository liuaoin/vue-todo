<template>
  <div id="footer">
    <span>Written by {{author}}</span>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  data() {
    return {
      author: 'liu liang',
    };
  },
};
</script>

<style lang="scss" scoped>
  #footer {
    margin-top: 40px;
    text-align: center;
    color: #bfbfbf;
    font-size: 10px;
    text-shadow: 0 1px 0 #fff;
  }
</style>
