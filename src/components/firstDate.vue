<script>
   export default {
      
   }
</script>

<template>
   <div class="firstDate">
      <div class="firstDate_date">08.09.2023</div>
      <div class="secondDate_date">Cостоится наша свадьба!</div>
      <div class="thirdDate_date">В этот день мы хотим соединить наши судьбы и сердца. <br>Нам будет очень приятно, если вы разделите с нами радость этого события!</div>

   </div>
</template>

<style scoped>
@font-face {
   font-family: 'Caravan';
   src: url('../fonts/Caravan.eot');
   src: local('Caravan'),
      url('../fonts/Caravan.eot') format('embedded-opentype'),
      url('../fonts/Caravan.woff2') format('woff2'),
      url('../fonts/Caravan.woff') format('woff'),
      url('../fonts/Caravan.ttf') format('truetype');
   font-weight: normal;
   font-style: normal;
}

.firstDate {
   padding-top: 50px;
   text-align: center;
   height: 825px;
   background-color: rgba(217, 217, 217, 1);
}
.firstDate_date {
   font-family: Caravan;
   font-size: 200px;
}
.secondDate_date {
   
   font-size: 50px;
   font-style: italic;
   margin-top: 100px;
}
.thirdDate_date {
   font-size: 40px;
   margin-top: 100px;

}

</style>