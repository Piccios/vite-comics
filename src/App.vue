<script>
  import AppHeader from './components/AppHeader.vue'
  import AppMain from './components/AppMain.vue'
  import AppFooter from './components/AppFooter.vue'
  import AppCards from './components/AppCards.vue'

  export default {
    data(){
      return {
        message: "prova"
      }
    },
    components: 
    {
      AppHeader,
      AppMain,
      AppCards,
      AppFooter
    },
    data(){
      return{

      }
    },
    methods: {

    },
    created(){

    }
  }
</script>

<template>
  <header>
    <AppHeader/>
  </header>
  <main>
    <AppCards/>
  </main>
  <footer>
    <AppFooter/>
  </footer>
</template>

<style lang="scss" >
  @use './styles/partials/variables.scss' as *;
  @use './styles/style.scss';
  </style>
