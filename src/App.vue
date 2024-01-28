<script setup>
import MyHello from "./components/MyHello.vue";
</script>

<template>
  <MyHello title="Pume" :sena="12500" :added="false" />
  <MyHello title="Nike" :sena="1252100" :added="true" />
</template>
