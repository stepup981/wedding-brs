<script>
   export default {
      name: 'Location'
   }
</script>

<template>
   <div class="location">
      <img
         class="location__img"
         src="../assets/img/studio.png"
      > 
      <div class="location__flexright">
         <div class="location__place">Место проведения
            <div class="location__place-logo">location</div>
         </div>
         <div class="location__adress">Торжество пройдет по адресу: <br>г. Киров, ул. Ленина, 101А
         </div>
         <div class="location__studio">STUDIO 101</div>
         <a
            class="location__link"
            href="https://yandex.ru/maps/org/studio_101/170069430179/?ll=49.686669%2C58.593822&z=12"
            target="_blank"
         >*посмотреть на карте</a>
      </div>
      
   </div>
</template>

<style lang="scss">
.location {
   background-color: rgba(239, 232, 226, 1);
   padding: 100px 100px 100px 0;
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
      position: absolute;
      z-index: -1;
      width: fit-content;
      transform: translate(25%, -75%);
      font-family: Caravan;
      font-size: 350px;
      color:rgba(177, 199, 222, 1);
   }

   &__flexright {
      display: flex;
      flex-direction: column;
      text-align: center;
      gap: 100px;
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
      text-decoration: none;
      z-index: 3;
   }
}

@media (max-width:480px) {
   .location {
   background-color: rgba(239, 232, 226, 1);
   padding: 50px 30px 50px 0;
   display: flex;
   align-items: center;
   flex-direction: row;
   background-image: url(../assets/img/flower.png);
   background-repeat: no-repeat;
   background-position: 100% 80%;
   background-size: 100px;

   &__img{
      width: 220px;
      height: 250px;
   }

   &__place {
      font-size: 35px;
      font-family: Journalism;
      position: relative;
      z-index: 1;
   }

   &__place-logo {
      position: absolute;
      z-index: -1;
      width: fit-content;
      transform: translate(-25%, -85%);
      font-family: Caravan;
      font-size: 150px;
      color:rgba(177, 199, 222, 1);
   }

   &__flexright {
      display: flex;
      flex-direction: column;
      text-align: center;
      gap: 13px;
   }

   &__adress {
      font-size: 15px;
   }

   &__studio {
      font-size: 45px;
      font-family: Journalism;
      color: rgba(34, 70, 107, 1);
   }

   &__link {
      font-size: 15px;
      color: black;
      text-decoration: none;
      z-index: 3;
   }
}
}
</style>