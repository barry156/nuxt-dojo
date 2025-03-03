<template>
    <div>
       <header>
            <nav>
                <NuxtLink to="/">Nuxt to Dojo</NuxtLink>
                <ul>
                    <li><nuxt-link to="/">Home</nuxt-link></li>
                    <li><nuxt-link to="/about">About</nuxt-link></li>
                    <li><nuxt-link to="/products">Products</nuxt-link></li>
                </ul>
                <a href="/about"> normal link -- about page</a>
            </nav>
       </header>
    </div>
</template>

<script setup>

</script>

<style  scoped>
    h2 {
        margin-bottom : 20 px;
        font-size: 36 px;
    }
    p {
        color: #333;
        margin: 20 px 0;
    }

</style>