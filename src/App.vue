<template>
  <div id="app" class="uk-overflow-hidden">
    <Navbar/>
    <Home/>
    <!-- <Profile/> -->
    <Story/>
    <Gallery/>
    <Invitation/>
    <Support/>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Home from './components/Home'
// import Profile from './components/Profile'
import Gallery from './components/Gallery'
import Story from './components/Story'
import Invitation from './components/Invitation'
import Support from './components/Support'

export default {
  name: 'app',
  components: {
    Navbar, Home, Gallery, Story, Invitation, Support
  },
  head: {
    title: {
      inner: 'Damaris & Omar',
      separator: '-',
      complement: 'Nuestra boda'
    },
    // Meta tags
    meta: [
      { name: 'application-name', content: 'Invitación a la boda' },
      { name: 'description', content: 'Damaris & Omar celebra con nosotros', id: 'desc' }, 
    ],
    // link tags
    link: [
      ]
  }
}
</script>

<style lang="scss">
  //$colorprimary : #dd183f;
  $colorprimary : #a17188;

  @import url('https://fonts.googleapis.com/css?family=Niconne');

  body h1, .uk-logo {
    font-family: 'Niconne', cursive !important;
    font-size: 35px !important;
  }
  .title {
    color: #ffffff !important;
    font-size: 30px !important;
    padding-top: 10px !important;
    padding-bottom: 10px !important;
  }
  .title:hover, .title:focus {
    color: #000000 !important;
  }
  .uk-heading-line {
   // background: #ef5974 !important;
    background: #a17188 !important;
  }   
  
  @media screen and (max-width: 1024px) {
     body h1, .uk-logo {
      font-family: 'Niconne', cursive !important;
      font-size: 35px !important;
    }
    p {
      font-size: 14px !important;
    } 
    h1 {
      font-size: 25px !important;
    }
    .title {
      padding-top: 10px !important;
      padding-bottom: 10px !important;
    }
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
  }
</style>