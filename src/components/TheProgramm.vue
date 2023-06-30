<template>
   <div class="programm">
      <div class="programm__title">Программа
         <div class="programm__title-logo">programm</div>
      </div>
         <ul class="programm__vector">
            <li>15:30 – сбор гостей</li>
            <li>16:00 – торжественная церемония</li>
            <li>16:30 – фуршет, фото с гостям</li>
            <li>17:00 – праздничный банкет</li>
         </ul>
   </div>
</template>

<script>
   export default {
      
   }
</script>

<style lang="scss">
.programm {
   background-color: rgba(177, 199, 222, 1);
   padding: 130px 130px;
   display: flex;
   flex-direction: column;
   gap: 100px;
  

   &__title {
      font-size: 90px;
      font-family: Journalism;
      text-align: center;
      padding-left: 550px;
      position: relative;
      z-index: 1;
   }

   &__title-logo {
      font-size: 350px;
      font-family: Caravan;
      color: rgba(239, 232, 226, 1);
      position: absolute;
      z-index: -1;
      transform: translate(-20%, -100%);
   }

   &__vector {
      font-size: 35px;

   }
}
</style>