<script setup>
	import Breadcrumbs from "./Breadcrumbs.vue";
	import AsideV2 from "./Aside.vue";
	import Calculator from "./Calculator.vue";
	import AdBlockSecond from "./AdBlockSecond.vue";
	import Description from "./Description.vue";
</script>

<template>
    <section id="calc" class="my-10">
        <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
            <Breadcrumbs />
            <div class="mt-2">
                <h2 class="text-2xl font-medium tracking-tight text-gray-700">
                    Калькулятор веса
                </h2>
            </div>
            <div class="flex flex-col lg:flex-row gap-10 mt-6">
                <main class="flex-1">
                    <Calculator />
                    <AdBlockSecond />
                    <Description />
                </main>
                <AsideV2 />
            </div>
        </div>
    </section>
</template>