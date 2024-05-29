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
                        <svg class="w-6" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                            fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                            stroke-linejoin="round">
                            <circle cx="11" cy="11" r="8" />
                            <path d="m21 21-4.3-4.3" />
                        </svg>
                    </button>
                    <div class="inline-flex hs-dropdown relative">
                        <button id="hs-dropdown-user" type="button"
                            class="hs-dropdown-toggle p-2 font-semibold text-gray-700 bg-white rounded-lg hover:bg-gray-100 active:bg-gray-200 flex items-center gap-x-2 hs-dropdown-open:bg-gray-100">
                            <svg class="w-6" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round">
                                <circle cx="12" cy="8" r="5" />
                                <path d="M20 21a8 8 0 0 0-16 0" />
                            </svg>
                        </button>

                        <div class="hs-dropdown-menu transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-60 bg-white shadow-md rounded-lg p-2 mt-2 border"
                            aria-labelledby="hs-dropdown-user">
                            <div class="py-3 px-5 -m-2 bg-gray-100 rounded-t-lg">
                                <p class="text-gray-500">Выполнен вход как</p>
                                <p class="font-medium text-gray-700">james@site.com
                                </p>
                            </div>
                            <div class="divide-y divide-gray-200 pt-2">
                                <div class="py-2 last:pb-0">
                                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                                        href="#">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" class="w-5">
                                            <path
                                                d="M2.7 10.3a2.41 2.41 0 0 0 0 3.41l7.59 7.59a2.41 2.41 0 0 0 3.41 0l7.59-7.59a2.41 2.41 0 0 0 0-3.41l-7.59-7.59a2.41 2.41 0 0 0-3.41 0Z" />
                                        </svg>
                                        Сохраненные расчеты
                                    </a>
                                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg  text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                                        href="#">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" class="w-5">
                                            <polygon
                                                points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2" />
                                        </svg>
                                        Избранные калькуляторы
                                    </a>
                                </div>
                                <div class="py-2 last:pb-0">
                                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                                        href="#">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                                            viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" class="w-5">
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
                                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg  text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                                        href="#">
                                        <svg class="w-5" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
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
                            class="p-2 font-semibold text-gray-700 bg-white rounded-lg hover:bg-gray-100 active:bg-gray-200 flex items-center gap-x-2"
                            data-hs-overlay="#hs-overlay-menu">
                            <svg class="w-6" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
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
                <div class="p-4 overflow-y-auto">
                    <div class="">
                        <input type="text" autofocus
                            class="py-3 px-4 block w-full border-gray-200 rounded-lg text-sm focus:border-primary-500 focus:ring-primary-500 disabled:opacity-50 disabled:pointer-events-none"
                            placeholder="Найти калькулятор">
                    </div>
                    <div>

                    </div>
                </div>
            </div>
        </div>
    </div>









    <div id="hs-overlay-menu"
        class="hs-overlay hs-overlay-open:translate-x-0 hidden translate-x-full fixed top-0 end-0 transition-all duration-300 transform h-full max-w-xs w-full z-[80] bg-white border-s"
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
        <div class="px-4 h-[calc(100vh-4rem)] !overflow-y-auto pb-4">
            <div class="divide-y divide-gray-200 pt-2">
                <div class="py-2 first:pt-0 last:pb-0">
                    <span class="block py-2 px-3 text-sm font-medium uppercase text-gray-400">
                        Финансовые калькуляторы
                    </span>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Кредитный калькулятор
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Ипотечный калькулятор
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Кредитный калькулятор с досрочным погашением
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор рефинансирования
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор микрозаймов
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор инфляции
                    </a>
                </div>
                <div class="py-2 first:pt-0 last:pb-0">
                    <span class="block py-2 px-3 text-sm font-medium uppercase text-gray-400">
                        Калькуляторы для инвестиций
                    </span>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор вкладов
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор инвестиций
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор доходности облигаций
                    </a>
                </div>
                <div class="py-2 first:pt-0 last:pb-0">
                    <span class="block py-2 px-3 text-sm font-medium uppercase text-gray-400">
                        Бухгалтерия и налоги
                    </span>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор НДС
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор НДФЛ
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор пеней
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор имущественного вычета
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор налога с продажи квартиры
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор процентов по займу
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор процентов по статье 395 ГК РФ
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор неустойки
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Сумма прописью
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор стажа
                    </a>
                </div>
                <div class="py-2 first:pt-0 last:pb-0">
                    <span class="block py-2 px-3 text-sm font-medium uppercase text-gray-400">
                        Автомобильные калькуляторы
                    </span>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор ОСАГО
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор транспортного налога
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор автокредита
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор растаможки автомобилей
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор расхода топлива
                    </a>
                    <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-sm text-gray-700 hover:bg-gray-100 focus:outline-none focus:bg-gray-100"
                        href="#">
                        Калькулятор зарядки электромобилей
                    </a>
                </div>
                
            </div>
        </div>
    </div>




</template>