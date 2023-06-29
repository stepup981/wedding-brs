<script>
  export default {
		name: 'Header'
}
</script>

<template>
  <div class="header">
		<div class="header-list">
			<button class="header__btn">Потвердить присутствие</button>
			<a class="header-list__item">Место проведения</a>
			<div class="header-list__item-logo">
				Роман и Екатерина
				<div class="header-list__item-absolute">love</div>
			</div>
			<a class="header-list__item">Программа</a>
			<a class="header-list__item">Стиль</a>
			<a class="header-list__item">Детали</a>
		</div>
  </div>
</template>

<style lang="scss">
.header {
  position: sticky;
  top: 0;
  padding: 16px 40px;
  background-color: #fff;

	&__btn {
		font-size: 18px;
		color: #fff;
		background-color:  rgba(34, 70, 107, 1);
		border-radius: 40px;
		padding: 4px;
		outline: none;
		border: none;
		cursor: pointer;

		&:hover {
			box-shadow: 0px 0px 35px 31px rgba(153, 155, 156, 0.2);
		}
	}
}

.header-list {
  display: grid;
  grid-template-columns: 1fr repeat(2, 1.5fr) repeat(3, 1fr);
  align-items: center;

	&__item {
		font-size: 18px;
		text-align: center;
		margin: 0 auto;
    width: fit-content;
		cursor: pointer;

		&:hover {
			color: rgba(188, 157, 128, 1);
			text-decoration: underline;
		}
	}

	&__item-logo {
		font-size: 32px;
		font-family: Journalism;
		text-align: center;
		position: relative;
		z-index: 1;
	}

	&__item-absolute {
		position: absolute;
		transform: translate(0, -80%);
		font-size: 225px;
		font-family: Caravan;
		color: #B1C7DE;
		z-index: 5;
	}
}
</style>