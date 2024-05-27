<template>
    <button class="flex items-center justify-center gap-2 rounded-lg border py-2 px-3 hover:border-gray-400" data-hs-overlay="#search-overlay">
        <svg class="h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path d="m18.031 16.617 4.283 4.282-1.415 1.415-4.282-4.283A8.96 8.96 0 0 1 11 20c-4.968 0-9-4.032-9-9s4.032-9 9-9 9 4.032 9 9a8.96 8.96 0 0 1-1.969 5.617Zm-2.006-.742A6.977 6.977 0 0 0 18 11c0-3.868-3.133-7-7-7-3.868 0-7 3.132-7 7 0 3.867 3.132 7 7 7a6.977 6.977 0 0 0 4.875-1.975l.15-.15Z"></path>
        </svg>
        <span class="hidden sm:block">Поиск</span>
    </button>


    <div id="search-overlay" 
        class="hs-overlay hs-overlay-open:translate-y-0 hs-overlay-backdrop-open:bg-gray-900/50 hs-overlay-backdrop-open:backdrop-blur-sm hs-overlay-backdrop-open:!z-[49]
        -translate-y-full fixed top-0 inset-x-0 transition-all duration-300 transform  !z-[100] bg-white border-b hidden" tabindex="-1">
        <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 py-10">
            <div class="flex items-start justify-between">
                <h1 class="text-4xl font-medium tracking-tight text-gray-900">
                    Поиск
                </h1>
                <button type="button" class="inline-block rounded-lg px-2 py-2 text-sm text-gray-700 hover:bg-gray-100 hover:text-gray-900" data-hs-overlay="#search-overlay">
                    <span class="sr-only">Close modal</span>
                    <svg class="h-6" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M18 6 6 18"></path>
                        <path d="m6 6 12 12"></path>
                    </svg>
                </button>
            </div>
            <div class="mt-6">
                <input type="text" 
                    class="py-3 px-4 block w-full border-gray-200 rounded-lg text-sm focus:border-primary-500 focus:ring-primary-500 disabled:opacity-50 disabled:pointer-events-none" 
                    placeholder="Найти калькулятор"
                    value="Каль"
                    autofocus>
            </div>
            <div class="text-start grid sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 xl:gap-6 mt-6">
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium">Кредитный <span class="text-primary-500">каль</span>кулятор</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium">Ипотечный <span class="text-primary-500">каль</span>кулятор</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium">Кредитный <span class="text-primary-500">каль</span>кулятор с досрочным погашением</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium"><span class="text-primary-500">Каль</span>кулятор рефинансирования</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium"><span class="text-primary-500">Каль</span>кулятор микрозаймов</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium"><span class="text-primary-500">Каль</span>кулятор инфляции</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium"><span class="text-primary-500">Каль</span>кулятор вкладов</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium"><span class="text-primary-500">Каль</span>кулятор инвестиций</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium"><span class="text-primary-500">Каль</span>кулятор доходности облигаций</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium"><span class="text-primary-500">Каль</span>кулятор ИМТ</h3>
                </a>
                <a href="#" class="flex items-center justify-center p-4 text-center relative rounded-xl before:absolute before:inset-0 before:z-10 before:border before:border-gray-200 before:rounded-xl before:transition before:hover:border-2 before:hover:border-primary-500 before:hover:shadow-lg">
                    <h3 class="text-base text-gray-900 font-medium"><span class="text-primary-500">Каль</span>кулятор веса</h3>
                </a>
            </div>
        </div>
    </div>
</template>