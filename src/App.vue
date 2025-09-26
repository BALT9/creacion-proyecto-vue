<script setup lang="ts">
import { ref } from "vue";

let titulo = ref<string>("proyecto vue con ts");
let numero = ref<number>(200);


</script>

<template>
  <h1>{{ titulo }}</h1>
  <p>{{ numero }}</p>
</template>
