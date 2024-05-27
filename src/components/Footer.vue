<script setup>
	import Logo from "./Logo.vue";
</script>

<template>
    <footer class="border-t border-gray-200">
        <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
            <div class="py-16">

                <div class="flex items-center justify-center">
                    <Logo />
                </div>

                <nav class="mt-10">
                    <div class="flex items-center justify-center flex-wrap gap-x-6">
                        <a class="inline-block rounded-lg px-3 py-2 text-sm text-gray-700 hover:bg-gray-100 hover:text-gray-900" href="#">
                            Поддержка
                        </a>
                        <a class="inline-block rounded-lg px-3 py-2 text-sm text-gray-700 hover:bg-gray-100 hover:text-gray-900" href="#">
                            Политика конфиденциальности
                        </a>
                        <a class="inline-block rounded-lg px-3 py-2 text-sm text-gray-700 hover:bg-gray-100 hover:text-gray-900" href="#">
                            Пользовательское соглашение
                        </a>
                        <a class="inline-block rounded-lg px-3 py-2 text-sm text-gray-700 hover:bg-gray-100 hover:text-gray-900" href="#faqs">
                            Часто задаваемые вопросы (FAQ)
                        </a>
                    </div>
                </nav>

            </div>

            <div class="flex flex-col items-center border-t border-gray-200 py-10 md:flex-row-reverse md:justify-between">

                <div class="flex gap-x-6">
                    <a class="group" aria-label="TaxPal on X" href="#">
                        <svg class="h-6 w-6 fill-gray-500 group-hover:fill-gray-800" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="m20.665 3.72-17.73 6.837c-1.21.486-1.203 1.16-.222 1.462l4.552 1.42 10.532-6.645c.498-.303.953-.14.579.192l-8.533 7.7H9.84l.002.002-.314 4.692c.46 0 .663-.211.92-.46l2.212-2.15 4.599 3.397c.848.467 1.457.227 1.668-.785l3.019-14.228c.309-1.24-.473-1.8-1.282-1.434Z"></path>
                        </svg>
                    </a>
                    <a class="group" aria-label="TaxPal on GitHub" href="#">
                        <svg class="h-6 w-6 fill-gray-500 group-hover:fill-gray-800" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M12 2c2.717 0 3.056.01 4.122.06 1.065.05 1.79.217 2.428.465.66.254 1.216.598 1.772 1.153.509.5.902 1.105 1.153 1.772.247.637.415 1.363.465 2.428.047 1.066.06 1.405.06 4.122 0 2.717-.01 3.056-.06 4.122-.05 1.065-.218 1.79-.465 2.428a4.883 4.883 0 0 1-1.153 1.772c-.5.508-1.105.902-1.772 1.153-.637.247-1.363.415-2.428.465-1.066.047-1.405.06-4.122.06-2.717 0-3.056-.01-4.122-.06-1.065-.05-1.79-.218-2.428-.465a4.89 4.89 0 0 1-1.772-1.153 4.904 4.904 0 0 1-1.153-1.772c-.248-.637-.415-1.363-.465-2.428C2.013 15.056 2 14.717 2 12c0-2.717.01-3.056.06-4.122.05-1.066.217-1.79.465-2.428a4.88 4.88 0 0 1 1.153-1.772A4.897 4.897 0 0 1 5.45 2.525c.638-.248 1.362-.415 2.428-.465C8.944 2.013 9.283 2 12 2Zm0 5a5 5 0 1 0 0 10 5 5 0 0 0 0-10Zm6.5-.25a1.25 1.25 0 1 0-2.5 0 1.25 1.25 0 0 0 2.5 0ZM12 9a3 3 0 1 1 0 6 3 3 0 0 1 0-6Z"></path>
                        </svg>
                    </a>
                </div>
                
                <div>
                    <p class="mt-6 text-sm text-gray-500 md:mt-0">
                        2024 © calcutor.ru
                    </p>
                    <p class="text-xs text-gray-400">
                        При использовании материалов сайта необходима ссылка на источник.
                    </p>
                </div>

            </div>
        </div>
    </footer>
</template>