<script setup>
import Label from "../../components/Label.vue";
import Input from "../../components/Input.vue";
import Button from "../../components/Button.vue";
</script>

<template>
  <div class="auth-box">
    <div class="form-box">
      <h2 class="auth-tittle">Login to your Account</h2>
      <div class="input-box">
        <Label text="Email adress" />
        <Input id="email" type="text" placeholde="email@example.org" />

        <Label text="Password" />
        <Input id="email" type="password" placeholde="**********" />

        <Button text="Login" />
      </div>
    </div>
  </div>
  <div class="auth-help-box">
    <p class="auth-help">
      Don't have an account? <RouterLink to="/register">Register</RouterLink>
    </p>
    <p class="auth-help">
      Forgoten yout password? <a href="">Recover Password</a>
    </p>
  </div>
</template>

<style>
.auth-box {
  background-color: #f5f7f8;
  width: 400px;
  border-radius: 5px;
  position: relative;
  overflow: hidden;
}

.form-box {
  margin: 3rem;
}

.auth-tittle {
  font-weight: 500;
  text-align: left;
  margin: 0;
  letter-spacing: 1px;
  color: #3d4954;
}

.input-box {
  margin-top: 2rem;
  width: 100%;
}

.auth-help-box {
  margin-top: 20px;
}

.auth-help {
  font-size: 12px;
  margin: 0;
}

.auth-help > a {
  font-weight: 700;
  color: #fff;
  text-decoration: none;
}
</style>
