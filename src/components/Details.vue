<script>
   export default {
      name: "Details"
   }
</script>

<template>
   <div class="details-style">
      <div class="details-style__title">
         Детали
            <div class="details-style__logo">
               datails
            </div>         
      </div>
         <div class="details-style__info">Никакой официальности, суеты и торжественных речей. <br>
         Только близкие люди, без которых<br>
         мы не представляем этот день, непринужденная<br> 
         атмосфера и много веселья!
         </div>
         <div class="details-style__hostimg">
            <div class="details-style__host">Творческие поздравления 
            приветствуются. Детали у нашего
            ведущего vk.com/islam_gaf
            </div>
            <img class="details-style__islamimg" src="../assets/img/islam.png">
         </div>
         <div class="details-style__organizerimg">
            <div class="details-style__organizer">По всем вопросам в день свадьбы
            обращайтесь к нашему организатору
            Валерии тел. +7-922-999-83-72.
            </div>
            <img class="details-style__leraimg" src="../assets/img/lera.png">
         </div>
         <div class="details-style__accept">
            Подтвердите свое присутствие<br>
            на нашем торжестве не позднее 23.07.2023.
               <div class="details-style__acceptlogo">
                  Пожалуйста
               </div>
         </div>
   </div>
</template>

<style lang="scss">
.details-style {
   padding: 132px 150px;
   background-color: #efe9e3;
   display: flex;
   flex-direction: column;
   gap: 80px;

   &__title {
      font-size: 75px;
      font-family: Journalism;
      position: relative;
      z-index: 1;
   }

   &__logo {
      font-size: 350px;
      font-family: Caravan;
      color: rgba(188, 157, 128, 1);
      width: fit-content;
      position: absolute;
      z-index: -1;
      transform: translate(-25%, -95%);
   }

   &__info {
      font-size: 36px;
      text-align: center;
   }

   &__hostimg {
      display: flex;
      justify-content: space-between;
   }

   &__host {
      font-size: 36px;
      text-align: left;
   }

   &__islamimg {
      height: 400px;
   }

   &__organizerimg {
      display: flex;
      justify-content: space-between;
   }

   &__organizer {
      font-size: 36px;
      text-align: left;
   }

   &__leraimg {
      height: 400px;
   }

   &__accept {
      font-size: 40px;
      text-align: center;
      position: relative;
      z-index: 1;
   }

   &__acceptlogo {
      font-size: 350px;
      font-family: Caravan;
      color: rgba(177, 199, 222, 1);
      width: fit-content;
      position: absolute;
      z-index: -1;
      transform: translate(-15%, -115%);
   }
}

@media (max-width:480px) {
   .details-style {
   padding: 60px 30px;
   background-color: #efe9e3;
   display: flex;
   flex-direction: column;
   gap: 40px;

   &__title {
      font-size: 35px;
      font-family: Journalism;
      position: relative;
      z-index: 1;
   }

   &__logo {
      font-size: 150px;
      font-family: Caravan;
      color: rgba(188, 157, 128, 1);
      width: fit-content;
      position: absolute;
      z-index: -1;
      transform: translate(-5%, -75%);
   }

   &__info {
      font-size: 20px;
      text-align: center;
   }

   &__hostimg {
      display: flex;
      justify-content: space-between;
   }

   &__host {
      font-size: 16px;
      text-align: left;
   }

   &__islamimg {
      height: 110px;
   }

   &__organizerimg {
      display: flex;
      justify-content: space-between;
   }

   &__organizer {
      font-size: 16px;
      text-align: left;
   }

   &__leraimg {
      height: 110px;
   }

   &__accept {
      font-size: 20px;
      text-align: center;
      position: relative;
      z-index: 1;
   }

   &__acceptlogo {
      font-size: 130px;
      font-family: Caravan;
      color: rgba(177, 199, 222, 1);
      width: fit-content;
      position: absolute;
      z-index: -1;
      transform: translate(-5%, -85%);
   }
}
}

</style>