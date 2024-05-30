<script setup>
	// import HeaderCo from "./components/Header.vue";
	import Hero from "./components/Hero.vue";
	import Catalog from "./components/Catalog.vue";
	// import CatalogDark from "./components/CatalogDark.vue";
	// import Prising from "./components/Prising.vue";
	// import Faq from "./components/Faq.vue";
	// import FooterCo from "./components/Footer.vue";
	// import Calc from "./components/Calc.vue";


	import HeaderV2 from "./components/v2/Header.vue";
	import FooterV2 from "./components/v2/Footer.vue";
	import CalcV2 from "./components/v2/Calc.vue";
</script>

<template>
  	<div class="min-h-screen flex flex-col">
    	<HeaderV2 />
		<main class="flex-1 bg-stone-50">
			<CalcV2 />

			<!-- <div id="main">
				<Hero />
				<Catalog />
			</div> -->


			<!-- <div id="calc">
				<Calc />
			</div> -->



			<!-- <div id="faq">
				<Faq />
			</div> -->


			

		</main>

    	<FooterV2 />

  	</div>
</template>
