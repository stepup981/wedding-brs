<script>
   export default {
      
   }
</script>

<template>
   <div class="location">
      <img class="location__img" src="../assets/img/studio.png"> 
      <div class="location__flexright">
         <div class="location__place">Место проведения
            <div class="location__place-logo">location</div>
         </div>
         <div class="location__adress">Торжество пройдет по адресу: <br>г. Киров, ул. Ленина, 101А
         </div>
         <div class="location__studio">STUDIO 101</div>
         <a class="location__link" href="https://yandex.ru/maps/org/studio_101/170069430179/?ll=49.681372%2C58.594623&z=14.2">*посмотреть на карте</a>
      </div>
      
   </div>
</template>

<style lang="scss">
.location__flexright {
   display: flex;
   flex-direction: column;
   text-align: center;
   grid-gap: 100px;
   padding-right: 100px;
}
.location {
   background-color: rgba(239, 232, 226, 1);
   padding-top: 100px;
   padding-bottom: 100px;
   display: flex;
   align-items: center;
   flex-direction: row;
   background-image: url(../assets/img/flower.png);
   background-repeat: no-repeat;
   background-position: 100% 130%;

   &__img{
      width: 1000px;
      height: 700px;
      
   }
   &__place {
      font-size: 75px;
      font-family: Journalism;
      position: relative;
      z-index: 1;
   }

   &__place-logo {
      font-size: 350px;
      color:rgba(177, 199, 222, 1);
      font-family: Caravan;
      position: absolute;
      transform: translate(15%, -75%);
      z-index: -1;

   }

   &__adress {
      font-size: 35px;
   }

   &__studio {
      font-size: 120px;
      font-family: Journalism;
      color: rgba(34, 70, 107, 1);
   }

   &__link {
      font-size: 35px;
      color: black;
   }
}
   

</style>