<template>
    <div>
      <button @click="emitData">Kirim Data ke Parent</button>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      emitData() {
        this.$emit('data', 'Data dari ChildComponent');
      }
    }
  }
  </script>
  