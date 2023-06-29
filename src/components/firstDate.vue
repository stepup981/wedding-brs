<script>
   export default {
      
   }
</script>

<template>
   <div class="date">
      <div class="first__date">08.09.2023</div>
      <div class="second__date">Cостоится наша свадьба!</div>
      <div class="third__date">В этот день мы хотим соединить наши судьбы и сердца. <br>Нам будет очень приятно, если вы разделите с нами радость этого события!</div>

   </div>
</template>

<style scoped>
@font-face {
   font-family: 'Caravan';
   src: url('../assets/fonts/Caravan.eot');
   src: local('Caravan'),
      url('../assets/fonts/Caravan.eot') format('embedded-opentype'),
      url('../assets/fonts/Caravan.woff2') format('woff2'),
      url('../assets/fonts/Caravan.woff') format('woff'),
      url('../assets/fonts/Caravan.ttf') format('truetype');
   font-weight: normal;
   font-style: normal;
}

.date {
   padding-top: 50px;
   text-align: center;
   background-color: rgba(217, 217, 217, 1);
}
.first__date {
   font-family: Caravan;
   font-size: 120px;
}
.second__date {
   
   font-size: 35px;
   font-style: italic;
   margin-top: 80px;
}
.third__date {
   font-size: 35px;
   margin-top: 80px;
}

</style>