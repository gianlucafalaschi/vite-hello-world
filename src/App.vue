<script> 
  
  import AppTitle from './components/AppTitle.vue';
  import AppHero from './components/AppHero.vue';
  
  export default {    
    components: {
      AppTitle,
      AppHero,
      
    }
  }
</script>

<template>
      <!-- Qui aggiungo html -->
      <main>
        <AppTitle></AppTitle>
        <AppHero></AppHero>
      </main>
</template>


<style scoped>
  /* Qui aggiungiamo CSS */
</style>

<!-- Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i 
  vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita 
"La mia prima app con Vite!"
Bonus:
Creare un secondo componente AppHero, che visualizza un jumbotron. -->