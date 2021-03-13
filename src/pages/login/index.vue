<template>
  <div class="wrap">
    <div class="">
      <label class="l-title">欢迎登录！</label>
      <div class="l-content">
        <div style="margin-bottom:20px">
          <input
            type="text"
            class="f-input"
            placeholder="请输入账号"
            v-model="form.username"
          />
        </div>
        <div style="margin-bottom:20px">
          <input
            type="text"
            class="f-input"
            placeholder="请输入密码"
            v-model="form.username"
          />
        </div>
        <div style="margin-bottom:20px">
          <button type="button" class="btn btn-success">登录</button>
        </div>
        <div>
          <span>忘记密码？</span>
          <span>没有账号，去<span>注册</span></span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "login",
  data() {
    return {
      form: {
        username: "",
        password: "",
      },
    };
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
    background: rgba(255, 255, 255, 0.5);
    border-radius: 14px;
  }
}
.f-input {
  background: none;
  height: 40px;
  border: 1px solid #fff;
  width: 100%;
  border-radius: 24px;
}
</style>
