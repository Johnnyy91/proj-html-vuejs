<template>
  <div id="app">
    <HeaderComponent :navbartext="navbar"/>
    <MainComponent />
    <FooterComponent :footerlink="footerlink"/>
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
        },
        {
          text: 'ABOUT',
        },
        {
          text: 'SERVICES',
        },
        {
          text: 'PRICING',
        },
        {
          text: 'BLOG',
        },
        {
          text: 'GET IN TOUCH',
        }
      ],
      footerlink: [
        {
          about : 'The Company' ,
          inst : 'Institutional',
          service : 'Education',
        },
        {
          about: 'The Company',
          inst: 'Institutional',
          service: 'Education',
        },
        {
          about: 'The Company',
          inst: 'Institutional',
          service: 'Education',
        },
        {
          about: 'The Company',
          inst: 'Institutional',
          service: 'Education',
        },
        {
          about: 'The Company',
          inst: 'Institutional',
          service: 'Education',
        },
        {
          about: 'The Company',
          inst: 'Institutional',
          service: 'Education',
        },
      ]
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

section{
  padding: 100px 0;
}
</style>
