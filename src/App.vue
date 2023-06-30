<script>
import Header from '@/components/Header.vue'
import WeddingDate from '@/components/WeddingDate.vue'
import Location from '@/components/Location.vue'
import Programm from '@/components/Programm.vue'
import WeddingStyle from '@/components/WeddingStyle.vue'

export default {
  name: 'App',
  components: {
    Header,
    WeddingDate,
    Location,
    Programm,
    WeddingStyle
  }
}
</script>

<template>
  <div>
    <Header/>
    <WeddingDate/>
    <Location/>
    <Programm/>
    <WeddingStyle />
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,400;1,100;1,400&display=swap');

  @font-face {
    font-family: 'Caravan';
    src: url('./assets//fonts/Caravan.eot');
    src: local('Caravan'),
        url('./assets/fonts/Caravan.eot') format('embedded-opentype'),
        url('./assets/fonts/Caravan.woff2') format('woff2'),
        url('./assets/fonts/Caravan.woff') format('woff'),
        url('./assets/fonts/Caravan.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
  }

  @font-face {
    font-family: 'Journalism';
    src: local('Journalism'),
    url('./assets/fonts/Journalism.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
  }

  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
    width: 100%;
  }
</style>