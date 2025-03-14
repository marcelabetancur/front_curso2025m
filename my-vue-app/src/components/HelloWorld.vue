<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <p>
      Proveer accesibilidad medica para personas de todas las edades, para valorar el tiempo de cada uno y obtener una asistencia efectiva. 
      
    </p>
  </div>

  <p>
    Este esquema es un punto de partida y puede ajustarse según los proveedores, la complejidad del diseño y las negociaciones con las instituciones médicas.
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >
  </p>
  <p>
    Learn more about IDE Support for Vue in the
    <a
      href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support"
      target="_blank"
      >Vue Docs Scaling up Guide</a
    >.
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
