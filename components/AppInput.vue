<template>
  <div>
    <div class="relative flex items-center">
      <button
      class="absolute right-0 bg-blue-500 p-1 h-10 focus:outline-none text-lg font-bold text-white"
      >
        +
      </button>
      <input type="text"
      class="w-full h-10 border border-slate-300 rounded-full mb-4 focus:outline-none"
      placeholder="Escribir Nueva Tarea"
      >
    </div>
    <Card v-for="item in 5" :key="item"/>
  </div>
</template>
<script>
import Card from './Card.vue'
export default {

}
</script>

Card
