<template>
    <div>
        <header>
        <nav>
         <ul>
            <li><NuxtLink to="/">Home Page</NuxtLink></li>
         </ul>
        </nav>
    </header>
    </div>
    <div>
        <slot />
    </div>

    <footer>
        <ul>
                <li>
                    <NuxtLink to="/About">about</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/store/AppComp">App Comp</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li><NuxtLink to="/store/AppSite">App site</NuxtLink></li>
            </ul>
    </footer>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>