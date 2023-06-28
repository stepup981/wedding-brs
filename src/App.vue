<!-- <template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style> -->




<script>
import TheHeader from '@/components/TheHeader.vue'
import firstDate from '@/components/firstDate.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    firstDate
  }
}
</script>

<template>
  <div>
    <TheHeader>
      
    </TheHeader>
    <firstDate>
      
    </firstDate>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,400;1,100;1,400&display=swap');

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
  width: 100vw;
}

</style>