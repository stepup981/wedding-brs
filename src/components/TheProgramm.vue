<template>
   <div class="programm">
      <div class="programm__title">Программа</div>
      <div>15:30 – сбор гостей</div>
      <div>16:00 – торжественная церемония</div>
      <div>16:30 – фуршет, фото с гостями</div>
      <div>17:00 – праздничный банкет</div>
   </div>
</template>

<script>
   export default {
      
   }
</script>

<style lang="scss">
.programm {
   background-color: rgba(177, 199, 222, 1);
   background-image: url(../assets/img/floweprog.png);
   background-size: 300px;
   background-repeat: no-repeat;
   background-position: right bottom;
   padding: 50px;
   padding-top: 80px;
   font-size: 35px;
   // display: flex;
   // flex-direction: column;

   &__title {
      font-size: 90px;
      font-family: Journalism;
      text-align: center;
      // padding-right: 450px;
      padding-bottom: 120px;
   }
}
</style>