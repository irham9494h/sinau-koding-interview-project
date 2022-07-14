<script setup>
defineProps({
  text: String,
});
</script>

<template>
  <label class="form-label">{{ text }}</label>
</template>

<style>
.form-label {
  text-align: left;
  margin-bottom: 4px;
  float: left;
  font-size: 12px;
  color: #94949c;
  font-weight: 600;
}
</style>
