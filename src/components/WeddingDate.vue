<script>
   export default {
      name: "WeddingDate"
   }
</script>

<template>
	<div class="wedding-date">
		<div class="wedding-date__date">08.09.2023</div>
		<div class="wedding-date__title">Cостоится наша свадьба!</div>
		<div class="wedding-date__subtitle">В этот день мы хотим соединить наши судьбы и сердца. <br>Нам будет очень приятно, если вы разделите с нами радость этого события!</div>
		<div class="wedding-date__under">Рома <span style="font-family: Monserat; font-size: 100px;">+</span> Катя</div>
	</div>
</template>

<style lang="scss">
.wedding-date {
	padding: 50px 0 100px;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	gap: 48px;
	background-color: rgba(217, 217, 217, 1);
	text-align: center;

	&__date {
		font-family: Caravan;
		font-size: 150px;
	}

	&__title {
		font-size: 34px;
		font-style: italic;
		font-weight: 500;
	}

	&__subtitle {
		font-size: 34px;
	}
	&__under {
		color: #B1C7DE;
		font-size: 180px;
		font-family: Caravan;
		text-align: right;
		margin-bottom: -160px;
	}
}
</style>