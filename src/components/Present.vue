<script>
   export default {
      
   }
</script>

<template>
   <div class="present-style">
      <div class="present-style__title">Подарки
         <div class="present-style__style">present</div>
      </div>
      <div>Самым лучшим подарком для нас станут ваши улыбки, хорошее настроение. Красивые конверты с теплыми пожеланиями и финансовыми презентами.</div>
      <div>О цветах в этот день просим не беспокоиться. Будем рады, если вы замените их бутылочкой хорошего вина для нашей домашней коллекции.</div>
   </div>
</template>



<style lang="scss">
.present-style {
   display: flex;
   flex-direction: column;
   gap: 100px;
   padding: 100px;
   background-color: rgba(188, 157, 128, 1);
   font-size: 50px;
   background-image: url(../assets/img/vectordetail.png), url(../assets/img/vectordetail2.png);
   background-repeat: no-repeat, no-repeat;
   background-position: left, 50% 62%;
   background-size: 300px, 150px ;

   &__title {
      font-size: 90px;
      font-family: Journalism;
      position: relative;
      z-index: 1;
      text-align: center;
   }

   &__style {
      color: rgba(239, 232, 226, 1);
      font-size: 350px;
      font-family: Caravan;
      width: fit-content;
      position: absolute;
      z-index: -1;
      transform: translate(85%, -90%);
   }
}

@media (max-width:480px) {
   .present-style {
   display: flex;
   text-align: center;
   flex-direction: column;
   gap: 35px;
   padding: 45px;
   padding-top: 60px;
   background-color: rgba(188, 157, 128, 1);
   font-size: 20px;
   background-image: url(../assets/img/vectordetail.png), url(../assets/img/vectordetail2.png);
   background-repeat: no-repeat, no-repeat;
   background-position: 0% 65%, 50% 58%;
   background-size: 100px, 50px ;

   &__title {
      font-size: 35px;
      font-family: Journalism;
      position: relative;
      z-index: 1;
      text-align: center;
   }

   &__style {
      color: rgba(239, 232, 226, 1);
      font-size: 150px;
      font-family: Caravan;
      width: fit-content;
      position: absolute;
      z-index: -1;
      transform: translate(25%, -75%);
   }
}
}

</style>