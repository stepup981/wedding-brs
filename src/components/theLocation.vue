<script>
   export default {
      
   }
</script>

<template>
   <div class="loc">
      <img class="img" src="../assets/img/studio.png">
      <div class="loc__flex">
         <div class="loc__title">Место проведения</div>
         <div>Торжество пройдет по адресу: г. Киров, ул. Ленина, 101А</div>
         <div class="loc__studio">STUDIO 101</div>
         <a href="https://yandex.ru/maps/org/studio_101/170069430179/?ll=49.681372%2C58.594623&z=14">*посмотреть на карте</a>
      </div>

   </div>
</template>

<style scoped>

.loc {
   margin-top: 40px;
}
.img {
   height: 700px;
   width: 700px;
}
.loc__flex {
   display: flex;
   flex-direction:column;
   text-align: right;
}


</style>