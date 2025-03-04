<template>
    <div>
       <header>
            <nav>
                <NuxtLink to="/">Nuxt to Dojo</NuxtLink>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
                
            </nav>
       </header>

       <!-- output page content-->
        <div>
            <slot />
        </div>
    </div>
</template>
<style scoped>
    .router-link-exact-active {
        color: red;
    }
</style>