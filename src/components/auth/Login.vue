<script setup>
import Label from "../Label.vue";
import Input from "../Input.vue";
import Button from "../Button.vue";
</script>

<template>
  <div class="auth-box">
    <div class="form-box">
      <h2 class="auth-tittle">Login to your account</h2>
      <div class="input-box">
        <Label text="Email adress" />
        <Input id="email" type="text" placeholde="email@example.org" />

        <Label text="Email adress" />
        <Input id="email" type="password" placeholde="email@example.org" />

        <Button text="Login" />
      </div>
    </div>
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
</style>
