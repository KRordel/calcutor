<script setup>
	import Logo from "./Logo.vue";
	import Search from "./Search.vue";
</script>

<template>
    <header class="">
        <nav>
            <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 relative z-50 flex items-center justify-between py-8">
                <div class="relative z-10 flex items-center gap-16">
                    <Logo />
                </div>
                <div class="flex items-center gap-4">
                    
                    <Search />
                    <a class="hidden sm:flex items-center justify-center gap-2 rounded-lg border py-2 px-3 hover:border-gray-400" href="/login">
                        <svg class="h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M12 6a3.75 3.75 0 1 0 0 7.5A3.75 3.75 0 0 0 12 6Zm0 6a2.25 2.25 0 1 1 0-4.5 2.25 2.25 0 0 1 0 4.5Z"></path>
                            <path d="M12 1.5A10.5 10.5 0 1 0 22.5 12 10.512 10.512 0 0 0 12 1.5ZM7.5 19.782V18.75a2.253 2.253 0 0 1 2.25-2.25h4.5a2.253 2.253 0 0 1 2.25 2.25v1.032a8.924 8.924 0 0 1-9 0Zm10.494-1.088A3.751 3.751 0 0 0 14.25 15h-4.5a3.751 3.751 0 0 0-3.744 3.694 9 9 0 1 1 11.988 0Z"></path>
                        </svg>
                        Войти
                    </a>
                    <button type="button" data-hs-overlay="#hs-overlay-right" class="flex items-center justify-center gap-2 rounded-lg py-2 px-3 border
                        bg-gray-800 text-gray-200 border-gray-800 
                        hover:bg-gray-900 hover:text-white hover:border-gray-900">
                        <svg class="h-5" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M3.975 5.975h16"></path>
                            <path d="M3.975 11.975h16"></path>
                            <path d="M3.975 17.975h16"></path>
                        </svg>
                        Меню
                    </button>

                </div>
            </div>
        </nav>
    </header>


    <div id="hs-overlay-right" class="hs-overlay hs-overlay-open:translate-x-0 hidden translate-x-full fixed top-0 end-0 transition-all duration-300 transform h-full max-w-xs w-full z-[80] bg-white border-s dark:bg-neutral-800 dark:border-neutral-700" tabindex="-1">
        <div class="flex justify-between items-center py-3 px-4 border-b dark:border-neutral-700">
            <h3 class="text-2xl font-medium tracking-tight text-gray-900">
                Меню
            </h3>
            <button type="button" class="flex justify-center items-center size-7 font-semibold rounded-full border border-transparent text-gray-800 hover:bg-gray-100 disabled:opacity-50 disabled:pointer-events-none dark:text-white dark:hover:bg-neutral-700" data-hs-overlay="#hs-overlay-right">
                <span class="sr-only">Close modal</span>
                <svg class="flex-shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M18 6 6 18"></path>
                    <path d="m6 6 12 12"></path>
                </svg>
            </button>
        </div>
        <div class="p-4">
            <nav class="hs-accordion-group w-full flex flex-col flex-wrap" data-hs-accordion-always-open>
                <ul class="space-y-1.5">
                    <li>
                        <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                            <svg class="h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M12 6a3.75 3.75 0 1 0 0 7.5A3.75 3.75 0 0 0 12 6Zm0 6a2.25 2.25 0 1 1 0-4.5 2.25 2.25 0 0 1 0 4.5Z"></path>
                                <path d="M12 1.5A10.5 10.5 0 1 0 22.5 12 10.512 10.512 0 0 0 12 1.5ZM7.5 19.782V18.75a2.253 2.253 0 0 1 2.25-2.25h4.5a2.253 2.253 0 0 1 2.25 2.25v1.032a8.924 8.924 0 0 1-9 0Zm10.494-1.088A3.751 3.751 0 0 0 14.25 15h-4.5a3.751 3.751 0 0 0-3.744 3.694 9 9 0 1 1 11.988 0Z"></path>
                            </svg>
                            Войти
                        </a>
                    </li>
                    <li>
                        <a class="flex items-center gap-x-3.5 py-2 px-2.5 bg-gray-100 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-700 dark:text-white" href="#">
                            <svg class="h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M15 7v12.97l-5-2.15-5 2.15V7h10Zm4-6H8.99C7.89 1 7 1.9 7 3h10c1.1 0 2 .9 2 2v13l2 1V3c0-1.1-.9-2-2-2Zm-4 4H5c-1.1 0-2 .9-2 2v16l7-3 7 3V7c0-1.1-.9-2-2-2Z"></path>
                            </svg>
                            Мои расчеты
                        </a>
                    </li>
                    <li>
                        <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                            <svg class="h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M12 17.27 18.18 21l-1.64-7.03L22 9.24l-7.19-.61L12 2 9.19 8.63 2 9.24l5.46 4.73L5.82 21 12 17.27Z"></path>
                            </svg>
                            Избранные калькуляторы
                        </a>
                    </li>

             

                    <li class="hs-accordion" id="account-accordion">
                        <button type="button" class="hs-accordion-toggle hs-accordion-active:text-primary-600 hs-accordion-active:hover:bg-transparent w-full text-start flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 ">
                            <svg class="h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M23.25 19.5a.75.75 0 0 1-.75.75h-21a.75.75 0 1 1 0-1.5h21a.75.75 0 0 1 .75.75ZM1.528 9.208a.75.75 0 0 1 .328-.844l9.75-6a.74.74 0 0 1 .788 0l9.75 6a.75.75 0 0 1-.394 1.388H19.5v6H21a.75.75 0 0 1 0 1.5H3a.75.75 0 1 1 0-1.5h1.5v-6H2.25a.75.75 0 0 1-.722-.544ZM13.5 15.001a.75.75 0 1 0 1.5 0v-4.5a.75.75 0 1 0-1.5 0V15ZM9 15a.75.75 0 0 0 1.5 0v-4.5a.75.75 0 1 0-1.5 0V15Z"></path>
                            </svg>
                            Финансовые калькуляторы
                            <svg class="hs-accordion-active:rotate-180 ms-auto block size-4 text-gray-600 group-hover:text-gray-500 dark:text-neutral-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                        </button>
                        <div id="account-accordion" class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300 hidden">
                            <ul class="pt-2 ps-2">
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Кредитный калькулятор
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Ипотечный калькулятор
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Кредитный калькулятор с досрочным погашением
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Калькулятор рефинансирования
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Калькулятор микрозаймов
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Калькулятор инфляции
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </li>

                    <li class="hs-accordion" id="account-accordion">
                        <button type="button" class="hs-accordion-toggle hs-accordion-active:text-primary-600 hs-accordion-active:hover:bg-transparent w-full text-start flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 ">
                            <svg class="h-6" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M12 14.25c5.385 0 9.75-2.015 9.75-4.5s-4.365-4.5-9.75-4.5-9.75 2.015-9.75 4.5 4.365 4.5 9.75 4.5Z"></path>
                                <path d="M12 14.25v4.5"></path>
                                <path d="M2.25 9.75v4.5c0 2.25 3.75 4.5 9.75 4.5s9.75-2.25 9.75-4.5v-4.5"></path>
                                <path d="M18 13.32v4.5"></path>
                                <path d="M6 13.32v4.5"></path>
                            </svg>
                            Калькуляторы для инвестиций
                            <svg class="hs-accordion-active:rotate-180 ms-auto block size-4 text-gray-600 group-hover:text-gray-500 dark:text-neutral-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                        </button>
                        <div id="account-accordion" class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300 hidden">
                            <ul class="pt-2 ps-2">
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Калькулятор вкладов
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Калькулятор инвестиций
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Калькулятор доходности облигаций
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </li>

                    <li class="hs-accordion" id="account-accordion">
                        <button type="button" class="hs-accordion-toggle hs-accordion-active:text-primary-600 hs-accordion-active:hover:bg-transparent w-full text-start flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 ">
                            <svg class="h-6" fill="none" stroke="currentColor" stroke-linecap="round" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M3.95 2.5c1.419 1.51 2.128 3.47 2.128 5.882C6.078 12 3 14.77 2.484 16.75 2.142 18.07 1.98 19.654 2 21.5"></path>
                                <path d="M19.628 2.5C18.209 4.01 17.5 5.97 17.5 8.382c0 3.618 3.078 6.387 3.593 8.368.344 1.32.505 2.904.485 4.75"></path>
                                <path d="M3.122 15.418c3.263 2.065 6.225 3.097 8.889 3.097 2.663 0 5.479-1.032 8.449-3.097"></path>
                                <path fill="currentColor" stroke="none" d="M12 15.5a1.25 1.25 0 1 0 0-2.5 1.25 1.25 0 0 0 0 2.5Z"></path>
                            </svg>
                            Калькуляторы для здоровья
                            <svg class="hs-accordion-active:rotate-180 ms-auto block size-4 text-gray-600 group-hover:text-gray-500 dark:text-neutral-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                        </button>
                        <div id="account-accordion" class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300 hidden">
                            <ul class="pt-2 ps-2">
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Калькулятор ИМТ
                                    </a>
                                </li>
                                <li>
                                    <a class="flex items-center gap-x-3.5 py-2 px-2.5 text-gray-700 rounded-lg hover:bg-gray-100 dark:bg-neutral-800 dark:text-neutral-400 dark:hover:text-neutral-300" href="#">
                                        Калькулятор веса
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </li>

                
                </ul>
            </nav>
        </div>
    </div>
  

</template>