<template>
    <div>
        <div class="position-relative overflow-hidden p-3 p-md-5 text-center bg-light">
            <div class="col-md-5 p-lg-5 mx-auto my-3">
                <h1 class="display-4 font-weight-normal">{{ title }}</h1>
            </div>
            <div class="product-device shadow-sm d-none d-md-block"></div>
            <div class="product-device product-device-2 shadow-sm d-none d-md-block"></div>
        </div>
    </div>
</template>

<script setup>
    const { title } = defineProps(['title'])
</script>

<style scoped>
</style>