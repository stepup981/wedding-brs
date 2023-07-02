<script>
export default {
  name: "WeddingStyle"
}
</script>

<template>
  <div class="wedding-style">
    <div class="wedding-style__title">
      Стиль праздника
      <div class="wedding-style__style">
        style
      </div>
    </div>
    <div class="wedding-style__info">
      Мы хотим сделать праздник красивым и будем <br>
      рады, если вы поддержите цветовую гамму <br>
      свадьбы, выбирая свой праздничный наряд.
    </div>
    <div class="wedding-style__colors">
      <div class="wedding-style__color blue"></div>
      <div class="wedding-style__color deep-blue"></div>
      <div class="wedding-style__color beige"></div>
      <div class="wedding-style__color deep-beige"></div>
      <div class="wedding-style__color brown"></div>
      <div class="wedding-style__color black"></div>
    </div>
    <div class="wedding-style__grid">
      <div class="wedding-style__women">
        <div class="wedding-style__subtitle">Варианты  для дам</div>
        <div class="wedding-style__pics">
          <img
            src="../assets/img/women-1.png"
            class="wedding-style__pic"
          >
          <img
            src="../assets/img/women-2.png"
            class="wedding-style__pic"
          >
          <img
            src="../assets/img/women-3.png"
            class="wedding-style__pic"
          >
          <img
            src="../assets/img/women-4.png"
            class="wedding-style__pic"
          >
        </div>
      </div>
      <div class="wedding-style__men">
        <div class="wedding-style__subtitle">Варианты  для мужчин</div>
        <div class="wedding-style__pics">
          <img
            src="../assets/img/men-1.png"
            class="wedding-style__pic"
          >
          <img
            src="../assets/img/men-2.png"
            class="wedding-style__pic"
          >
          <img
            src="../assets/img/men-3.png"
            class="wedding-style__pic"
          >
          <img
            src="../assets/img/men-4.png"
            class="wedding-style__pic"
          >
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.wedding-style {
  padding: 132px 100px 60px;
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

  &__style {
    position: absolute;
    z-index: -1;
    width: fit-content;
    transform: translate(0,-95%);
    font-family: Caravan;
    font-size: 350px;
    color:rgba(177, 199, 222, 1);
  }

  &__info {
    font-size: 36px;
    text-align: end;
  }

  &__colors {
    display: flex;
    gap: 24px;
    justify-content: center;
  }

  &__color {
    width: 128px;
    height: 128px;
    border-radius: 50%;
  }

  &__grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 46px;
    justify-content: center;
    text-align: center;
  }

  &__women,
  &__men {
    display: flex;
    flex-direction: column;
  }

  &__subtitle {
    font-size: 36px;
    margin-bottom: 64px;
  }

  &__pics {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 36px;
  }

  &__pic {
    max-width: 256px;
  }

  .blue {
    background-color: #b1c7de;
  }

  .deep-blue {
    background-color: #244362;
  }

  .beige {
    background-color: #ceb9a6;
  }

  .deep-beige {
    background-color: #bc9d80;
  }

  .brown {
    background-color: #72462e;
  }

  .black {
    background-color: #000;
  }
}
</style>