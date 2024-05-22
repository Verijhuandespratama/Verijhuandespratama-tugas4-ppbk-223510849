<template>
    <div>
      <h1>Parent Component</h1>
      <ChildComponent @data="handleData" />
      <p>Data dari ChildComponent: {{ childData }}</p>
    </div>
  </template>
  
  <script>
  import ChildComponent from './ChildComponent.vue';
  
  export default {
    components: {
      ChildComponent
    },
    data() {
      return {
        childData: ''
      };
    },
    methods: {
      handleData(data) {
        this.childData = data;
      }
    }
  }
  </script>
  