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
	z-index: 5;
	
	&__btn {
		font-size: 18px;
		color: #fff;
		background-image: linear-gradient(to right, #0f0c29, #302b63, #24243e);
		border-radius: 40px;
		padding: 4px;
		outline: none;
		cursor: pointer;

		&:hover {
			box-shadow: rgba(0, 0, 0, 0.56) 0px 22px 70px 4px;
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
	position: relative;
	color: black;
	cursor: pointer;
	line-height: 1; 
	text-decoration: none; 
	
		&:after {
		display: block;
		position: absolute;
		left: 0; 
		width: 0;
		height: 2px; 
		background-color: rgba(188, 157, 128, 1); 
		content: "";
		transition: width 0.3s ease-out;
		}

		&:hover:after,
		&:focus:after {
		width: 100%; 
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
		z-index: -1;
	}
}
</style>