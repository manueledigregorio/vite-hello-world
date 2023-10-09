<template>
 
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  name:'AppTitle',
  data() {
    return {
      title: 'la mia prima app con  Vite!',
    }
  },
  
}
</script>

<style scoped>
  h1{
    text-align: center;
    margin-top: 30px;
  }
</style>