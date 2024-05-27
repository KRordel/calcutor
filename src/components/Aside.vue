<script setup>
	import AdBlock from "./AdBlock.vue";
</script>

<template>
    <aside class="lg:w-[300px] flex-none space-y-10">
        <AdBlock />
        <section>
            <div class="rounded-xl border p-4">
                <h4 class="text-gray-800 font-semibold leading-4 flex items-center gap-4">
                    <svg class="h-6 text-primary-500 flex-none" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path d="M3 4.5A1.5 1.5 0 0 1 4.5 3h12.64L21 6.603V19.5a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 19.5v-15Z"></path>
                        <path d="M12.004 3 12 6.692c0 .17-.224.308-.5.308h-4c-.276 0-.5-.138-.5-.308V3h5.004Z"></path>
                        <path d="M4.5 3h12.64"></path>
                        <path d="M7 13h10"></path>
                        <path d="M7 17h5.004"></path>
                    </svg>
                    Сохраненные расчеты
                </h4>
                <p class="text-sm text-gray-700 mt-4">
                    Вы можете сохранять ваши расчеты и они будут отображаться здесь.
                </p>
                <ul class="hidden space-y-1.5 mt-4">
                    <li>
                        <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100" href="#">
                            Имя сохраненного расчета 1
                        </a>
                    </li>
                    <li>
                        <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100" href="#">
                            Другой расчет
                        </a>
                    </li>
                </ul>
                
            </div>
        </section>
        <section>
            <div class="rounded-xl border p-4">
                <h4 class="text-gray-800 font-semibold leading-4 flex items-center gap-4">
                    <svg class="h-6 text-primary-500" fill="none" stroke="currentColor" stroke-linecap="round" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path d="M3.95 2.5c1.419 1.51 2.128 3.47 2.128 5.882C6.078 12 3 14.77 2.484 16.75 2.142 18.07 1.98 19.654 2 21.5"></path>
                        <path d="M19.628 2.5C18.209 4.01 17.5 5.97 17.5 8.382c0 3.618 3.078 6.387 3.593 8.368.344 1.32.505 2.904.485 4.75"></path>
                        <path d="M3.122 15.418c3.263 2.065 6.225 3.097 8.889 3.097 2.663 0 5.479-1.032 8.449-3.097"></path>
                        <path fill="currentColor" stroke="none" d="M12 15.5a1.25 1.25 0 1 0 0-2.5 1.25 1.25 0 0 0 0 2.5Z"></path>
                    </svg>
                    Калькуляторы для здоровья
                </h4>
                
                <ul class="space-y-1.5 mt-4">
                    <li>
                        <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100" href="#">
                            Калькулятор ИМТ
                        </a>
                    </li>
                    <li>
                        <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg bg-gray-100">
                            Калькулятор веса
                        </a>
                    </li>
                    <li>
                        <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100" href="#">
                            Кредитный калькулятор
                        </a>
                    </li>
                    <li>
                        <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100" href="#">
                            Ипотечный калькулятор
                        </a>
                    </li>
                    <li>
                        <a class="flex py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100" href="#">
                            Кредитный калькулятор с досрочным погашением
                        </a>
                    </li>
                </ul>
            </div>
        </section>
    </aside>
</template>