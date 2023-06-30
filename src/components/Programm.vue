<script>
export default {
   name: "Programm"
}
</script>

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
   display: flex;
   flex-direction: column;

   &__title {
      font-size: 90px;
      font-family: Journalism;
      text-align: center;
      padding-left: 450px;
      padding-bottom: 120px;
      position: relative;
      z-index: 1;
   }

   &__title-logo {
      font-size: 350px;
      font-family: Caravan;
      color: rgba(239, 232, 226, 1);
      position: absolute;
      z-index: -1;
      width: fit-content;
      transform: translate(15%, -105%);
   }

   &__vector {
      padding-left: 100px;
   }
}

</style>