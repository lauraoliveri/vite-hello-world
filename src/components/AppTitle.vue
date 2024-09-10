<script>
export default {
  data() {
    return { 
      Title: 'La mia prima app con Vite!'
    }
  }
}
</script>

<template>
  <header>
    <h1>
      {{ Title }}
    </h1>
  </header>
</template>

<style scoped>
header {
  text-align: center;
  padding: 20px 0;
}

h1 {
  color: blue;
}
</style>