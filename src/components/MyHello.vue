<script setup>
/* Composition API */
import { ref } from "vue";

defineProps({
  title: String,
  sena: Number,
  added: Boolean,
});
</script>

<template>
  <div class="product">
    <h1>Tovar {{ title }}</h1>
    <p>Sena : {{ sena }}</p>
    <p>Add: {{ added }}</p>
  </div>
</template>

<style scoped>
.product {
  padding: 12px 22px;
  border: 1px solid red;
  margin: 2px 0px;
}
</style>
