<template>
    <div>
        <header>
            <nav class="navbar navbar-expand-lg navbar-light">
                <NuxtLink class="navbar-brand px-5" to="/"><img src="../public/Logo.jpg" height="70"></NuxtLink>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarText">
                    <ul class="navbar-nav">
                        <li class="nav-item" v-for="navItem in navItems">
                            <NuxtLink class="nav-link px-4 text-light" :to="navItem.link">{{ navItem.title }}</NuxtLink>
                        </li>
                    </ul>
                </div>
            </nav>
        </header>

        <!-- Output the page content -->
        <div>
            <slot />
        </div>
    </div>
</template>

<script setup>
    const navItems = [
        {
            title: 'Home',
            link: '/',
        },
        {
            title: 'About Us',
            link: '/about',
        },
        {
            title: 'Products',
            link: '/products',
        },
        {
            title: 'Services',
            link: '/services',
        },
        {
            title: 'Contact',
            link: '/contact',
        },
    ]
</script>

<style scoped>
    nav {
        background-color: #468E82 !important;
    }

    nav a:hover {
        text-decoration: underline !important;
    }
</style>