<script>
   export default {
      
   }
</script>

<template>
   <div class="location">
      <div class="location__place">Место проведения</div>
      <div class="location__adress">Торжество пройдет по адресу: <br>г. Киров, ул. Ленина, 101А</div>
      <div class="location__studio">STUDIO 101</div>
      <a class="location__link" href="https://yandex.ru/maps/org/studio_101/170069430179/?ll=49.681372%2C58.594623&z=14.2">*посмотреть на карте</a>
   </div>
</template>

<style lang="scss">
.location {
   display: flex;
   flex-direction: column;
   background-image: url(../assets/img/studio.png);

   &__place {
      font-size: 90px;
      font-family: Journalism;
   }

   &__adress {
      font-size: 50px;
   }

   &__studio {
      font-size: 140px;
      font-family: Journalism;
      color: rgba(34, 70, 107, 1);
   }

   &__link {
      font-size: 50px;
      color: black;
   }
}
   

</style>