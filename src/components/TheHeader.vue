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
         <button class="header-btn">Потвердить присутствие</button>
         <div class="header-list-item"><a href="#"></a>Место проведения</div>
         <div class="header-list-item-logo">Роман и Екатерина</div>
         <div class="header-list-item"><a href="#"></a>Программа</div>
         
         <div class="header-list-item"><a href="#"></a>Стиль</div>
         <div class="header-list-item"><a href="#"></a>Детали</div>
      </div>
   </div>
</template>

<style scoped>
@import url(//db.onlinewebfonts.com/c/1f5855e73a9496b07c7dd77c7dc946fb?family=JOURNALISM);
.header {
   padding: 15px;
   /* margin-left: 140px; */
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
   color: rgba(188, 157, 128, 1);
   text-decoration: underline;
}
.header-list-item-logo {
   font-size: 35px;
   font-family: JOURNALISM;
}
.header-btn {
   margin-right: 55px;
   font-size: 20px;
   color: white;
   padding: 5px;
   border-right: 30px;
   border-left: 30px;
   border-radius: 40px;
   background-color:  rgba(34, 70, 107, 1);
   border-style: solid 2px black;
   
}

.header-btn:hover {
   box-shadow: 0px 0px 60px 31px rgba(153, 155, 156, 0.2);
}

</style>