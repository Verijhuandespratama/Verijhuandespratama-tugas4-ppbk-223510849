<template>
    <div>
      <h1>Parent Component</h1>
      <SlotComponent>
        <p>Data atau Component yang Akan Ditampilkan pada Parent</p>
      </SlotComponent>
    </div>
  </template>
  
  <script>
  import SlotComponent from './SlotComponent.vue';
  
  export default {
    components: {
      SlotComponent
    }
  }
  </script>
  