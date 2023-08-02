<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">Four T-Pop</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/Bowkylion" class="btn">Bowkylion</NuxtLink></li>
                    <li><NuxtLink to="/Inkwaruntorn" class="btn">Inkwaruntorn</NuxtLink></li>
                    <li><NuxtLink to="/Violettewautier" class="btn">Violettewautier</NuxtLink></li>
                    <li><NuxtLink to="/Zommarie" class="btn">Zommarie</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <!-- page content go here -->
        <div class="container mx-auto p-4">
            <slot />
        </div>
    </div>
</template>

<style scoped>
    .router-link-exact-active {
        color: #000000;
    }
</style>