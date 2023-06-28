<script>
   export default {
      name: 'TheHeader',
      components: {

      }
   }
</script>

<template>
   <div class="header">
      <div class="header-list">
         <div class="header-list-item"><a href="#"></a>Место проведения</div>
         <div class="header-list-item"><a href="#"></a>Программа</div>
         <div class="header-list-item-logo">Роман и Екатерина</div>
         <div class="header-list-item"><a href="#"></a>Стиль</div>
         <div class="header-list-item"><a href="#"></a>Детали</div>
      </div>
   </div>
</template>

<style scoped>

.header {
   padding: 15px;
   margin-left: 60px;
   width: 100vw;
   background-color: white;
}
.header-list {
   display: flex;
   justify-content: space-between;
   align-items: center;
}
.header-list-item {
   font-size: 20px;
}
.header-list-item:hover {
   color: rgb(70, 130, 180);
   text-decoration: underline;
}
.header-list-item-logo {
   font-size: 30px;
   font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
   padding-right: 100px;
}

</style>