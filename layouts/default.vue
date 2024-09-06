<template>
    <div>
        <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4 flex justify-between">
             <NuxtLink to="/" class="font-bld">HOME</NuxtLink>
            <ul class="flex gap-4">
                <li>
                    <NuxtLink to="/About">ABOUT</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/store/AppComp">APP COMP</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li><NuxtLink to="/store/AppSite">APP SITE</NuxtLink></li>
            </ul>
        </nav>
    </header>
    </div>
    <div class="container p-3 mx-auto">
        <slot />
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>