<script>
  import AppHeader from './components/AppHeader'
  import AppMain from './components/AppMain.vue'
  import AppFooter from './components/AppFooter.vue'
  export default {
    components: 
    {
      AppHeader,
      AppMain,
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
    <AppMain/>
  </main>
  <footer>
    <AppFooter/>
  </footer>
</template>

<style scoped>

</style>
