<script>
/* 
  Per importare ed utilizzare un componente dentro un altro devo SEMPRE seguire questi 3 passi:
  1) Importazione del componente
  2) Dichiarazione del componente
  3) Utilizzo del componente
*/
// 1) Importazione del componente
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';


export default {
  data() {
    return { 
      
    }
  },
  // 2) Dichiarazione del componente
  components: {
    AppTitle,
    AppHero
  },
  methods: {
    
  }
}
</script>

<template>
  <div>
    <!-- 3) Utilizzo del componente -->
    <AppTitle />
    <AppHero />
    
    <main>
    
    </main>
  </div>
</template>

<style scoped>
main {
  text-align: center;
}
</style>