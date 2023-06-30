<script>
export default {
   name: "Programm"
}
</script>

<template>
   <div class="programm">
      <div class="programm__title">Программа</div>
      <div>15:30 – сбор гостей</div>
      <div>16:00 – торжественная церемония</div>
      <div>16:30 – фуршет, фото с гостями</div>
      <div>17:00 – праздничный банкет</div>
   </div>
</template>


<style lang="scss">
.programm {
   background-color: rgba(177, 199, 222, 1);
   background-image: url(../assets/img/floweprog.png);
   background-size: 300px;
   background-repeat: no-repeat;
   background-position: right bottom;
   padding: 80px 100px 50px;
   font-size: 36px;

   &__title {
      font-size: 90px;
      font-family: Journalism;
      text-align: center;
      padding-bottom: 120px;
   }
}
</style>