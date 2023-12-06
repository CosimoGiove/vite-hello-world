<script>
/**
 * Import
 * 
 * 1. importare il componente
 * 2. registrare il componente
 * 3. uso del componente in template in forma di tag
 * 
 */
// import HelloWorld from './components/HelloWorld.vue'
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  name: 'App',
  data(){
    return {
     
    }
  },
  components: {
    AppTitle,
    AppHero
    
  },
}
</script>

<template>
  <div>  
    <AppTitle />
    <AppHero/>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
