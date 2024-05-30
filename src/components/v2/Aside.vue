<script setup>
	import AdBlock from "./AdBlock.vue";
</script>

<template>
    <aside class="lg:w-[300px] flex-none space-y-10"> 
        <AdBlock />

        <section>
            <div class="rounded-lg border bg-white shadow-sm">
                <div class="border-b px-4 py-2">
                    <h4 class="font-semibold text-gray-700 flex items-center gap-3.5">
                        <svg class="w-5 h-5 flex-none" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M3 4.5A1.5 1.5 0 0 1 4.5 3h12.64L21 6.603V19.5a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 19.5v-15Z"></path>
                            <path d="M12.004 3 12 6.692c0 .17-.224.308-.5.308h-4c-.276 0-.5-.138-.5-.308V3h5.004Z"></path>
                            <path d="M4.5 3h12.64"></path>
                            <path d="M7 13h10"></path>
                            <path d="M7 17h5.004"></path>
                        </svg>
                        Сохраненные расчеты
                    </h4>
                </div>
                <div class="p-4">
                    <p class="text-sm text-gray-700 mb-4">
                        Вы можете сохранять ваши расчеты и они будут отображаться здесь.
                    </p>
                    <ul class="space-y-1.5">
                        <li>
                            <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100 focus:bg-gray-200" href="#">
                                Имя сохраненного расчета 1
                            </a>
                        </li>
                        <li>
                            <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100 focus:bg-gray-200" href="#">
                                Другой расчет
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </section>
        <section>
            <div class="rounded-lg border bg-white shadow-sm">
                <div class="border-b px-4 py-2">
                    <h4 class="font-semibold text-gray-700 flex items-center gap-3.5">
                        Калькуляторы для здоровья
                    </h4>
                </div>
                <div class="p-4">
                    <ul class="space-y-1.5">
                        <li>
                            <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100 focus:bg-gray-200" href="#">
                                Калькулятор ИМТ
                            </a>
                        </li>
                        <li>
                            <span class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg bg-gray-100 cursor-default select-none">
                                Калькулятор веса
                            </span>
                        </li>
                    </ul>
                </div>
            </div>
        </section>
    </aside>
</template>