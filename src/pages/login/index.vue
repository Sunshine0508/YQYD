<template>
  <div class="wrap">
    <label class="l-title">欢迎登录！</label>
    <div class="l-content">
      <form action=""></form>
    </div>
  </div>
</template>

<script>
export default {
  name: "login",
  data() {
    return {};
  },
  methods: {},
};
</script>

<style lang="scss" scoped>
.wrap {
  background: #8ea7e6;
  height: 100vh;
  box-sizing: border-box;
  .l-title {
    color: #fff;
    font-size: 24px;
  }
  .l-content {
    width: 410px;
    padding: 40px 50px;
    background-color: rgb(255, 255, 255);
    opacity: 0.3;
    border-radius: 14px;
    // position: relative;
  }
}
</style>
