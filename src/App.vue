<template>
  <div id="app">
    <SiteHeader
    :openTime="openTime"
    :contacts="contacts"
    />
    <div class="sitemain">
      <section class="one jumbosection">
        <div class="jumbotext"></div>
      </section>

      <section class="two">

      </section>

      <section class="three">

      </section>

      <section class="four">

      </section>

      <section class="five">

      </section>

      <section class="six">

      </section>

      <section class="seven">

      </section>

      <section class="eight">
      
      </section> 
      
    </div>

    <footer>

    </footer>
    
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue';

export default {
  name: 'App',
  components: {
    SiteHeader
  },
  data(){
    return {

      openTime: {
        "openingDay": "Mon",
        "closingDay": "Sat",
        "openingHour": "9:00",
        "closingHour": "18:00",
      },

      contacts: {
        "phoneNumber": "+1 (305) 1234-5678",
        "mailAddress": "hello@example.com",
        "address": "Main Avenue, 987"
      }

    }
  }
}
</script>

<style lang="scss">
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
//   margin-top: 60px;
// }

@import '../node_modules/bootstrap/dist/css/bootstrap.css';
@import './assets/common.scss';
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500;700&display=swap'); 

* {
  font-family: 'Open Sans', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
