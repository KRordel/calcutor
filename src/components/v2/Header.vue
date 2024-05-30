<script setup>
    import LogoV2 from "./Logo.vue";
</script>

<template>
    <header class="h-16 border-b">
        <div class="h-full max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="h-full flex items-center justify-between gap-x-10">
                <LogoV2 />
                <div class="flex items-center gap-x-2 sm:gap-x-6">
                    <button
                        class="p-2 font-semibold text-gray-700 bg-white rounded-lg hover:bg-gray-100 active:bg-gray-200 flex items-center gap-x-2"
                        data-hs-overlay="#hs-search-modal">
                        <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                            stroke-linecap="round" stroke-linejoin="round">
                            <circle cx="11" cy="11" r="8" />
                            <path d="m21 21-4.3-4.3" />
                        </svg>
                    </button>
                    <div class="inline-flex hs-dropdown relative">
                        <button id="hs-dropdown-user" type="button"
                            class="hs-dropdown-toggle p-2 font-semibold text-gray-700 bg-white rounded-lg hover:bg-gray-100 active:bg-gray-200 flex items-center gap-x-2 hs-dropdown-open:bg-gray-100">
                            <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round">
                                <circle cx="12" cy="8" r="5" />
                                <path d="M20 21a8 8 0 0 0-16 0" />
                            </svg>
                        </button>

                        <div class="hs-dropdown-menu transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-60 bg-white shadow-md rounded-lg p-2 mt-2 border"
                            aria-labelledby="hs-dropdown-user">
                            <div class="py-3 px-5 -m-2 bg-gray-100 rounded-t-lg">
                                <p class="text-sm text-gray-500">Выполнен вход как</p>
                                <p class="font-medium text-sm text-gray-700">james@site.com
                                </p>
                            </div>
                            <div class="divide-y divide-gray-200 pt-2">
                                <div class="py-2 last:pb-0">
                                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                                        href="#">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" class="w-4 h-4">
                                            <path
                                                d="M2.7 10.3a2.41 2.41 0 0 0 0 3.41l7.59 7.59a2.41 2.41 0 0 0 3.41 0l7.59-7.59a2.41 2.41 0 0 0 0-3.41l-7.59-7.59a2.41 2.41 0 0 0-3.41 0Z" />
                                        </svg>
                                        Сохраненные расчеты
                                    </a>
                                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                                        href="#">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" class="w-4 h-4">
                                            <polygon
                                                points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2" />
                                        </svg>
                                        Избранные калькуляторы
                                    </a>
                                </div>
                                <div class="py-2 last:pb-0">
                                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                                        href="#">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" class="w-4 h-4">
                                            <path d="M2 21a8 8 0 0 1 10.434-7.62" />
                                            <circle cx="10" cy="8" r="5" />
                                            <circle cx="18" cy="18" r="3" />
                                            <path d="m19.5 14.3-.4.9" />
                                            <path d="m16.9 20.8-.4.9" />
                                            <path d="m21.7 19.5-.9-.4" />
                                            <path d="m15.2 16.9-.9-.4" />
                                            <path d="m21.7 16.5-.9.4" />
                                            <path d="m15.2 19.1-.9.4" />
                                            <path d="m19.5 21.7-.4-.9" />
                                            <path d="m16.9 15.2-.4-.9" />
                                        </svg>
                                        Профиль
                                    </a>
                                </div>
                                <div class="py-2 last:pb-0">
                                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                                        href="#">
                                        <svg class="w-4 h-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round">
                                            <path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4" />
                                            <polyline points="16 17 21 12 16 7" />
                                            <line x1="21" x2="9" y1="12" y2="12" />
                                        </svg>
                                        Выход
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="sm:border-l sm:pl-6">
                        <button
                            class="p-2 font-semibold text-sm text-gray-700 bg-white rounded-lg hover:bg-gray-100 active:bg-gray-200 flex items-center gap-x-2"
                            data-hs-overlay="#hs-overlay-menu">
                            <svg class="w-6 h-5" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round">
                                <line x1="3" x2="21" y1="6" y2="6" />
                                <line x1="3" x2="21" y1="12" y2="12" />
                                <line x1="3" x2="21" y1="18" y2="18" />
                            </svg>
                            <span class="hidden sm:block">Меню</span>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </header>








    <div id="hs-search-modal"
        class="hs-overlay-backdrop-open:backdrop-blur-sm hs-overlay hidden size-full fixed top-0 start-0 z-[80] overflow-x-hidden overflow-y-auto pointer-events-none">
        <div
            class="hs-overlay-open:mt-7 hs-overlay-open:opacity-100 hs-overlay-open:duration-500 mt-0 opacity-0 ease-out transition-all sm:max-w-lg sm:w-full m-3 sm:mx-auto h-[calc(100%-3.5rem)] min-h-[calc(100%-3.5rem)] flex items-center">
            <div
                class="w-full max-h-full overflow-hidden flex flex-col bg-white border shadow-sm rounded-xl pointer-events-auto">
                <div class="flex justify-between items-center py-3 px-4 border-b">
                    <h2 class="text-xl font-semibold text-gray-700">
                        Поиск
                    </h2>
                    <button type="button"
                        class="flex justify-center items-center size-9 text-sm font-semibold rounded-lg border border-transparent text-gray-800 hover:bg-gray-100 disabled:opacity-50 disabled:pointer-events-none"
                        data-hs-overlay="#hs-search-modal">
                        <span class="sr-only">Close</span>
                        <svg class="flex-shrink-0 size-5" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path d="M18 6 6 18"></path>
                            <path d="m6 6 12 12"></path>
                        </svg>
                    </button>
                </div>
                <div
                    class="p-4 overflow-y-auto [&::-webkit-scrollbar]:w-2 [&::-webkit-scrollbar-thumb]:rounded-full [&::-webkit-scrollbar-track]:bg-gray-100 [&::-webkit-scrollbar-thumb]:bg-gray-300">
                    <div class="">
                        <input type="text" autofocus
                            class="py-3 px-4 block w-full border-gray-200 rounded-lg text-sm focus:border-primary-500 focus:ring-primary-500 disabled:opacity-50 disabled:pointer-events-none"
                            placeholder="Найти калькулятор">
                    </div>
                    <div class="mt-4 space-y-6">
                        <div>
                            <h2 class="text-base font-semibold text-gray-700">
                                Финансовые калькуляторы
                            </h2>
                            <ul class="mt-2 space-y-1.5">
                                <li>
                                    <a class="py-3 px-5 rounded-lg text-sm text-gray-700 bg-gray-50 hover:text-white hover:bg-primary-600 transition flex items-center justify-between gap-4"
                                        href="#">
                                        <span>
                                            Кредитный калькулятор
                                        </span>
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            class="flex-none size-4">
                                            <path d="m9 18 6-6-6-6" />
                                        </svg>
                                    </a>
                                </li>
                                <li>
                                    <a class="py-3 px-5 rounded-lg text-sm text-gray-700 bg-gray-50 hover:text-white hover:bg-primary-600 transition flex items-center justify-between gap-4"
                                        href="#">
                                        Ипотечный калькулятор
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            class="flex-none size-4">
                                            <path d="m9 18 6-6-6-6" />
                                        </svg>
                                    </a>
                                </li>
                            </ul>
                        </div>
                        <div>
                            <h2 class="text-base font-semibold text-gray-700">
                                Калькуляторы для инвестиций
                            </h2>
                            <ul class="mt-2 space-y-1.5">
                                <li>
                                    <a class="py-3 px-5 rounded-lg text-sm text-gray-700 bg-gray-50 hover:text-white hover:bg-primary-600 transition flex items-center justify-between gap-4"
                                        href="#">
                                        Кредитный калькулятор
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            class="flex-none size-4">
                                            <path d="m9 18 6-6-6-6" />
                                        </svg>
                                    </a>
                                </li>
                                <li>
                                    <a class="py-3 px-5 rounded-lg text-sm text-gray-700 bg-gray-50 hover:text-white hover:bg-primary-600 transition flex items-center justify-between gap-4"
                                        href="#">
                                        Ипотечный калькулятор
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round"
                                            class="flex-none size-4">
                                            <path d="m9 18 6-6-6-6" />
                                        </svg>
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>









    <div id="hs-overlay-menu"
        class="hs-overlay hs-overlay-open:translate-x-0 hs-overlay-backdrop-open:backdrop-blur-sm hidden translate-x-full fixed top-0 end-0 transition-all duration-300 transform h-full max-w-xs w-full z-[80] bg-white border-s"
        tabindex="-1">
        <div class="h-16 flex justify-between items-center px-4 border-b">
            <h2 class="text-xl font-semibold text-gray-700">
                Меню
            </h2>
            <button type="button"
                class="flex justify-center items-center size-9 text-sm font-semibold rounded-lg border border-transparent text-gray-800 hover:bg-gray-100 disabled:opacity-50 disabled:pointer-events-none"
                data-hs-overlay="#hs-overlay-menu">
                <span class="sr-only">Close</span>
                <svg class="flex-shrink-0 size-5" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                    viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                    stroke-linejoin="round">
                    <path d="M18 6 6 18"></path>
                    <path d="m6 6 12 12"></path>
                </svg>
            </button>

        </div>
        <div
            class="p-4 h-[calc(100vh-4rem)] !overflow-y-auto [&::-webkit-scrollbar]:w-2 [&::-webkit-scrollbar-thumb]:rounded-full [&::-webkit-scrollbar-track]:bg-gray-100 [&::-webkit-scrollbar-thumb]:bg-gray-300">
            <nav class="hs-accordion-group w-full flex flex-col flex-wrap">
                <ul class="space-y-1.5">
                    <li class="hs-accordion" id="accordion-id-1">
                        <button type="button"
                            class="hs-accordion-toggle hs-accordion-active:bg-gray-100 w-full text-start flex items-center gap-x-3.5 py-2 px-2.5 font-medium text-sm text-gray-700 rounded-lg hover:bg-gray-100">
                            Финансовые калькуляторы
                            <svg class="hs-accordion-active:rotate-180 ms-auto block size-4 text-gray-600 group-hover:text-gray-500 transition"
                                xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round">
                                <path d="m6 9 6 6 6-6" />
                            </svg>
                        </button>
                        <div id="accordion-id-1"
                            class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300 hidden">
                            <ul class="pt-2 ps-2">
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Кредитный калькулятор
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Ипотечный калькулятор
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Кредитный калькулятор с досрочным погашением
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор рефинансирования
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор микрозаймов
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор инфляции
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </li>
                    <li class="hs-accordion" id="accordion-id-2">
                        <button type="button"
                            class="hs-accordion-toggle hs-accordion-active:bg-gray-100 w-full text-start flex items-center gap-x-3.5 py-2 px-2.5 font-medium text-sm text-gray-700 rounded-lg hover:bg-gray-100">
                            Калькуляторы для инвестиций
                            <svg class="hs-accordion-active:rotate-180 ms-auto block size-4 text-gray-600 group-hover:text-gray-500 transition"
                                xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round">
                                <path d="m6 9 6 6 6-6" />
                            </svg>
                        </button>
                        <div id="accordion-id-2"
                            class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300 hidden">
                            <ul class="pt-2 ps-2">
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор вкладов
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор инвестиций
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор доходности облигаций
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </li>
                    <li class="hs-accordion" id="accordion-id-3">
                        <button type="button"
                            class="hs-accordion-toggle hs-accordion-active:bg-gray-100 w-full text-start flex items-center gap-x-3.5 py-2 px-2.5 font-medium text-sm text-gray-700 rounded-lg hover:bg-gray-100">
                            Бухгалтерия и налоги
                            <svg class="hs-accordion-active:rotate-180 ms-auto block size-4 text-gray-600 group-hover:text-gray-500 transition"
                                xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round">
                                <path d="m6 9 6 6 6-6" />
                            </svg>
                        </button>
                        <div id="accordion-id-3"
                            class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300 hidden">
                            <ul class="pt-2 ps-2">
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор НДС
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор НДФЛ
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор пеней
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор имущественного вычета
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор налога с продажи квартиры
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор процентов по займу
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор процентов по статье 395 ГК РФ
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор неустойки
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Сумма прописью
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор стажа
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </li>
                    <li class="hs-accordion" id="accordion-id-4">
                        <button type="button"
                            class="hs-accordion-toggle hs-accordion-active:bg-gray-100 w-full text-start flex items-center gap-x-3.5 py-2 px-2.5 font-medium text-sm text-gray-700 rounded-lg hover:bg-gray-100">
                            Автомобильные калькуляторы
                            <svg class="hs-accordion-active:rotate-180 ms-auto block size-4 text-gray-600 group-hover:text-gray-500 transition"
                                xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round">
                                <path d="m6 9 6 6 6-6" />
                            </svg>
                        </button>
                        <div id="accordion-id-4"
                            class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300 hidden">
                            <ul class="pt-2 ps-2">
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор ОСАГО
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор транспортного налога
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор автокредита
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор растаможки автомобилей
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор расхода топлива
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор зарядки электромобилей
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </li>
                    <li class="hs-accordion" id="accordion-id-5">
                        <button type="button"
                            class="hs-accordion-toggle hs-accordion-active:bg-gray-100 w-full text-start flex items-center gap-x-3.5 py-2 px-2.5 font-medium text-sm text-gray-700 rounded-lg hover:bg-gray-100">
                            Калькуляторы для здоровья
                            <svg class="hs-accordion-active:rotate-180 ms-auto block size-4 text-gray-600 group-hover:text-gray-500 transition"
                                xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round">
                                <path d="m6 9 6 6 6-6" />
                            </svg>
                        </button>
                        <div id="accordion-id-5"
                            class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300 hidden">
                            <ul class="pt-2 ps-2">
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор ИМТ
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100"
                                        href="#">
                                        Калькулятор веса
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </li>




                    <!-- <li>
                        <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-sm text-gray-700 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700 dark:text-neutral-400 dark:hover:text-neutral-300"
                            href="#">
                            <svg class="size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round">
                                <path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z" />
                                <path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z" />
                            </svg>
                            Documentation
                        </a>
                    </li> -->
                </ul>
            </nav>





        </div>
    </div>




</template>