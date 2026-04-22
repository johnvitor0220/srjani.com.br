<script setup>
import { CheckLineIcon, CircleCheckBigIcon, ClipboardCheckIcon, ClipboardIcon, DrillIcon, DropletsIcon, PlugZapIcon, ShelvingUnitIcon } from 'lucide-vue-next';

</script>

<template>
    <main
        class="bg-background-light dark:bg-background-dark text-white font-body min-h-screen flex flex-col items-center relative overflow-x-hidden transition-colors duration-300">
        <div class="fixed inset-0 bg-pattern z-0 pointer-events-none"></div>
        <main class="w-full max-w-4xl px-4 py-8 z-10 flex flex-col items-center gap-4">
            <header class="text-center w-full space-y-2 relative">
                <div class="flex items-center justify-center gap-3 mb-2">
                    <h2 class="text-xl md:text-2xl font-bold uppercase tracking-wide text-shadow-sm">
                        Precisa de ajuda com reparos em casa?
                    </h2>
                </div>
                <div class="relative inline-block">
                    <p class="text-2xl md:text-3xl italic font-display text-white/90">Sou</p>
                    <h1
                        class="text-5xl md:text-7xl font-display font-black text-primary uppercase text-shadow leading-tight tracking-tighter">
                        Marido de Aluguel
                    </h1>
                </div>
            </header>
            <section class="flex flex-col items-center">
                <div class="relative w-48 h-48 md:w-56 md:h-56">
                    <div class="absolute inset-0 bg-white/20 rounded-full animate-pulse"></div>
                    <div
                        class="absolute inset-2 bg-white rounded-full flex items-center justify-center border-4 border-custom-blue dark:border-background-dark shadow-xl overflow-hidden">
                        <div
                            class="w-full h-full bg-gradient-to-b from-blue-100 to-blue-50 flex items-end justify-center">
                            <img alt="Handyman portrait" class="w-full h-full object-cover"
                                src="./assets/images/ai-photo-2.jpeg" />
                        </div>
                    </div>
                </div>
                <div
                    class="mt-4 border-t-2 border-b-2 border-white/30 py-2 px-12 text-center backdrop-blur-sm bg-white/5 rounded-lg">
                    <h3 class="text-3xl font-display font-bold uppercase tracking-widest text-shadow">Sr. Janí</h3>
                </div>
            </section>
            <section>
                <div
                    class="w-full bg-primary -skew-x-6 transform shadow-lg mx-auto max-w-2xl py-3 px-6 rounded-sm relative group cursor-default hover:scale-105 transition-transform duration-300">
                    <div class="skew-x-6 text-center">
                        <p class="dark:text-gray-900  font-bold text-md md:text-base leading-tight">
                            Realizo diversos serviços domésticos e pequenos consertos com qualidade e confiança
                        </p>
                    </div>
                </div>
            </section>
            <section
                class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-4 text-lg md:text-xl font-medium w-full max-w-3xl">
                <div
                    class="flex items-center gap-3 bg-white/10 dark:bg-black/20 p-3 rounded-lg hover:bg-white/20 transition-colors cursor-default backdrop-blur-sm shadow-md border border-white/10">
                    <div class="bg-primary p-2 rounded text-custom-dark-green shadow-sm">
                        <span class="material-icons-outlined font-bold">
                            <PlugZapIcon class="h-8 w-8" />
                        </span>
                    </div>
                    <span class="text-white">Elétrica</span>
                </div>
                <div
                    class="flex items-center gap-3 bg-white/10 dark:bg-black/20 p-3 rounded-lg hover:bg-white/20 transition-colors cursor-default backdrop-blur-sm shadow-md border border-white/10">
                    <div class="bg-primary p-2 rounded text-custom-dark-green shadow-sm">
                        <span class="material-icons-outlined font-bold">
                            <DropletsIcon class="h-8 w-8" />
                        </span>
                    </div>
                    <span class="text-white">Hidráulica</span>
                </div>
                <div
                    class="flex items-center gap-3 bg-white/10 dark:bg-black/20 p-3 rounded-lg hover:bg-white/20 transition-colors cursor-default backdrop-blur-sm shadow-md border border-white/10">
                    <div class="bg-primary p-2 rounded text-custom-dark-green shadow-sm">
                        <span class="material-icons-outlined font-bold">
                            <ShelvingUnitIcon class="h-8 w-8" />
                        </span>
                    </div>
                    <span class="text-white">Montagem de móveis</span>
                </div>
                <div
                    class="flex items-center gap-3 bg-white/10 dark:bg-black/20 p-3 rounded-lg hover:bg-white/20 transition-colors cursor-default backdrop-blur-sm shadow-md border border-white/10">
                    <div class="bg-primary p-2 rounded text-custom-dark-green shadow-sm">
                        <span class="material-icons-outlined font-bold">
                            <DrillIcon class="h-8 w-8" />
                        </span>
                    </div>
                    <span class="text-white">Instalações em geral</span>
                </div>

            </section>

            <section class="mb-20">
                <div>
                    <p class="text-2xl md:text-3xl italic font-display text-white/90">
                        Técnico em manutenção residencial
                    </p>
                </div>
            </section>

            <a class="m-4 m-auto fixed md:bottom-4 md:right-4 bottom-4 z-50 bg-green-600 dark:bg-green-700 hover:bg-green-500 dark:hover:bg-green-600 text-white rounded-full p-2 pr-8 flex items-center shadow-lg hover:shadow-2xl hover:-translate-y-1 transition-all duration-300 border-2 border-green-400"
                href="https://wa.me/5542998610632?text=Ol%C3%A1,%20gostaria%20de%20me%20informar%20sobre%20o%20servi%C3%A7o%20de%20Marido%20de%20Aluguel%20">
                <div class="bg-white rounded-full p-3 mr-4 shadow-inner transition-transform duration-300">
                    <svg class="w-8 h-8 text-green-600 fill-current" viewBox="0 0 448 512"
                        xmlns="http://www.w3.org/2000/svg">
                        <path
                            d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.5 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z">
                        </path>
                    </svg>
                </div>
                <div class="flex flex-col text-left">
                    <span class="text-sm font-bold uppercase opacity-90 tracking-wide">Chame no WhatsApp</span>
                    <span class="text-2xl md:text-3xl font-display font-black tracking-wider">(42) 99861-0632</span>
                </div>
            </a>
        </main>
    </main>
</template>

<style scoped>
.text-shadow {
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

.text-shadow-sm {
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);
}

.bg-pattern {
    background-color: #026aa7;
    background-image: url("data:image/svg+xml,%3Csvg width='6' height='6' viewBox='0 0 6 6' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='%23055a8c' fill-opacity='0.4' fill-rule='evenodd'%3E%3Cpath d='M5 0h1L0 6V5zM6 5v1H5z'/%3E%3C/g%3E%3C/svg%3E");
}

.dark .bg-pattern {
    background-color: #0f172a;
    background-image: url("data:image/svg+xml,%3Csvg width='6' height='6' viewBox='0 0 6 6' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='%231e293b' fill-opacity='0.4' fill-rule='evenodd'%3E%3Cpath d='M5 0h1L0 6V5zM6 5v1H5z'/%3E%3C/g%3E%3C/svg%3E");
}

.floating-icon {
    animation: float 6s ease-in-out infinite;
}

@keyframes float {
    0% {
        transform: translateY(0px) rotate(0deg);
    }

    50% {
        transform: translateY(-10px) rotate(5deg);
    }

    100% {
        transform: translateY(0px) rotate(0deg);
    }
}
</style>
