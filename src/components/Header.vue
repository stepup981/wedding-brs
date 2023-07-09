<script>
	export default {
		methods: {
			clickHandler (location) {
				if (window.matchMedia("(max-width:480px)").matches) {
					window.scrollTo({top: document.querySelector(location).offsetTop -24,behavior: 'smooth'})
				} else {
					window.scrollTo({top: document.querySelector(location).offsetTop -74,behavior: 'smooth'})
				}
				// window.scrollTo({top: document.querySelector(location).offsetTop -94,behavior: 'smooth'})
			}
	}
}
</script>

<template>
	<div class="header">
		<div class="header-list">
			<a href="https://vk.me/join/b7SXSPtXUtCVHy7q1jYJ2fTZa28DlvHHPms=" target="_blank" class="header__btn">Подтвердить присутствие</a>
			<a @click="clickHandler('.location')" class="header-list__item">Место проведения</a>
			<div class="header-list__item-logo">
				Роман и Екатерина
				<div class="header-list__item-absolute">love</div>
			</div>
			<a @click="clickHandler('.programm')" class="header-list__item">Программа</a>
			<a @click="clickHandler('.wedding-style')" class="header-list__item">Стиль</a>
			<a @click="clickHandler('.present-style')" class="header-list__item">Подарки</a>
			<a @click="clickHandler('.details-style')" class="header-list__item">Детали</a>
		</div>
	</div>
</template>

<style lang="scss">
$color: rgb(22, 68, 117);

.header {
	position: sticky;
	top: 0;
	padding: 16px 30px;
	background-color: #fff;
	z-index: 5;
	
		&__btn {
		text-decoration: none;
		display: inline-block;
		padding: .25rem 1.25rem;
		border-radius: 10rem;
		color: #fff;
		text-transform: uppercase;
		font-size: 1rem;
		letter-spacing: .15rem;
		transition: all .3s;
		position: relative;
		overflow: hidden;
		text-align: center;
		z-index: 1;
		cursor: pointer;
		&:after {
			content: '';
			position: absolute;
			bottom: 0;
			left: 0;
			width: 100%;
			height: 100%;
			background-color: $color;
			border-radius: 10rem;
			z-index: -2;
		}
		&:before {
			content: '';
			position: absolute;
			bottom: 0;
			left: 0;
			width: 0%;
			height: 100%;
			background-color: darken($color, 15%);
			transition: all .3s;
			border-radius: 10rem;
			z-index: -1;
		}
		&:hover {
			color: #fff;
			&:before {
				width: 100%;
			}
		}
	}

.header-list {
	display: grid;
	grid-template-columns: 1.7fr repeat(2, 2.2fr) repeat(4, 1fr);
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
}

@media (max-width: 480px) {
	.header {
	position: sticky;
	top: 0;
	padding: 3px 4px;
	background-color: #fff;
	z-index: 5;
	
		&__btn {
		text-decoration: none;
		display: inline-block;
		padding: 4px 4px;
		border-radius: 10rem;
		color: #fff;
		text-transform: uppercase;
		font-size: 4px;
		letter-spacing: .1rem;
		transition: all .3s;
		position: relative;
		overflow: hidden;
		text-align: center;
		z-index: 1;
		cursor: pointer;
		&:after {
			content: '';
			position: absolute;
			bottom: 0;
			left: 0;
			width: 100%;
			height: 100%;
			background-color: $color;
			border-radius: 10rem;
			z-index: -2;
		}
		&:before {
			content: '';
			position: absolute;
			bottom: 0;
			left: 0;
			width: 0%;
			height: 100%;
			background-color: darken($color, 15%);
			transition: all .3s;
			border-radius: 10rem;
			z-index: -1;
		}
		&:hover {
			color: #fff;
			&:before {
				width: 100%;
			}
		}
	}

.header-list {
	display: grid;
	grid-template-columns: 1.7fr repeat(2, 2.2fr) repeat(4, 1fr);
	align-items: center;

	&__item {
	font-size: 8px;
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
		font-size: 12px;
		font-family: Journalism;
		text-align: center;
		position: relative;
		z-index: 1;
	}

	&__item-absolute {
		position: absolute;
		transform: translate(0, -55%);
		font-size: 95px;
		font-family: Caravan;
		color: #B1C7DE;
		z-index: -1;
	}
}
}
}

</style>