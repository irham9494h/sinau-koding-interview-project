<script setup>
defineProps({
  text: String,
});
</script>

<template>
  <button class="auth-button">{{ text }}</button>
</template>

<style>
.auth-button {
  background-color: #448bca;
  color: #fff;
  padding-top: 12px;
  padding-bottom: 12px;
  width: 100%;
  border-radius: 5px;
  font-weight: 600;
  font-size: 15px;
  border: 0;
}

.auth-button:hover {
  background-color: #6688aa;
  cursor: pointer;
}
</style>
