<template>
  <div id="app">
    <Navbar />
    <router-view/>
    <Jumbotron />
    <Features />
    <PortfolioComponent />
    <ResumeComponent />
    <TestimonialComponent />
    <nuovazona/>
    <frecciaSu />
   <ClientsComponent/>
   <MyBlog />
   <ContactMe />
    <appFooter />
 



  </div>

</template>

<script>
import Navbar from './components/Navbar.vue';
import Jumbotron from './components/Jumbotron.vue';
import frecciaSu from './components/frecciaSu.vue';
import Features from './components/Features.vue'; 
import PortfolioComponent from './components/PortfolioComponent.vue';
import ResumeComponent from './components/ResumeComponent.vue';
import appFooter from './components/appFooter.vue';
import TestimonialComponent from './components/TestimonialComponent.vue';
import nuovazona from './components/nuovazona.vue';
import MyBlog from './components/MyBlog.vue'
import ContactMe from './components/ContactMe.vue'
;import ClientsComponent from './components/ClientsComponent.vue';



export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
    frecciaSu,
    Features,
    PortfolioComponent,
    ResumeComponent,
    nuovazona,
    ContactMe,
    TestimonialComponent,
    MyBlog,
    appFooter,
    ClientsComponent,
    
 

  }  }

</script>


<style>

html body {
  font-family: 'Montserrat','Poppins', 'sans-serif';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #212529; 
  margin-top: 40px;
}


</style>