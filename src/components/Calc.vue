<script setup>
	import Breadcrumbs from "./Breadcrumbs.vue";
	import Aside from "./Aside.vue";
	import Calculator from "./Calculator.vue";
	import AdBlockSecond from "./AdBlockSecond.vue";
	import Description from "./Description.vue";
</script>

<template>
    <section id="calc" class="pb-20">
        <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
            <Breadcrumbs />
            <div class="mt-4">
                <h2 id="faqs-title" class="text-3xl font-medium tracking-tight text-gray-900">
                    Калькулятор веса
                </h2>
            </div>
            <div class="flex flex-col lg:flex-row gap-10 mt-10">
                <main class="flex-1">
                    <Calculator />
                    <AdBlockSecond />
                    <Description />
                </main>
                <Aside />
            </div>
        </div>
    </section>

</template>