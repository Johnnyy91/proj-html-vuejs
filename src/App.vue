<template>
  <div id="app">
    <HeaderComponent :navbartext="navbar"/>
    <MainComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';


export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
},
  data() {
    return {
      navbar: [
        {
          text: 'HOME',
          position: 1
        },
        {
          text: 'ABOUT',
          position: 2
        },
        {
          text: 'SERVICES',
          position: 3
        },
        {
          text: 'PRICING',
          position: 4
        },
        {
          text: 'BLOG',
          position: 5
        },
        {
          text: 'GET IN TOUCH',
          position: 6
        }
      ]
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
