<script>
import TheHeader from '@/components/TheHeader.vue'
import firstDate from '@/components/firstDate.vue'
import theLocation from '@/components/theLocation.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    firstDate,
    theLocation
  }
}
</script>

<template>
  <div>
    <TheHeader>
      
    </TheHeader>
    <firstDate>
      
    </firstDate>
    <theLocation>

    </theLocation>  
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,400;1,100;1,400&display=swap');

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
  width: 100%;
}

</style>