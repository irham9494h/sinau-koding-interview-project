<script setup>
defineProps({
  type: String,
  id: String,
  name: String,
  placeholde: String,
});
</script>

<template>
  <input
    class="form-input"
    :type="type"
    :id="id"
    :name="name"
    :placeholder="placeholde"
  />
</template>

<style>
.form-input {
  display: block;
  /* width: 100%; */
  padding: 0.6rem 0.75rem;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #212529;
  background-color: #ffffff;
  background-clip: padding-box;
  border: 1px solid #ced4da;
  appearance: none;
  border-radius: 3px;
  display: inline-block;
  margin-bottom: 20px;
}

.form-input:focus {
  outline: none !important;
  border: 1px solid #448bca;
  box-shadow: 0 0 5px #b5b9bd;
}

::placeholder {
  color: #c8cccc;
}
</style>
