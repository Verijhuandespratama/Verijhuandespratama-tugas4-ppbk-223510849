<!-- App.vue -->
<template>
  <div id="app">
    <h1>Tugas 4 Veri Jhuandes Pratama</h1>
    <!-- Tambahkan komponen ParentComponent di sini -->
    <ParentComponent />
  </div>
</template>

<script>
import ParentComponent from './components/ParentComponent.vue';

export default {
  components: {
    ParentComponent
  }
}
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  text-align: center;
}
</style>
