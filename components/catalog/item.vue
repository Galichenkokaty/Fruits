<template>
    <div class="catalog__item" :style="`background-color:#` + item.color">
        <div class="catalog__item-name">{{ item.name }}</div>
        <span class="catalog__item-text">Plant</span>
        <div v-if="item.img" class="catalog__item-img">
            <NuxtPicture class="thumb" :src="item.img" />
        </div>
        <div v-if="item.price" class="catalog__item-price">{{ item.price }}</div>
    </div>
</template>
<script setup>
    const { item } = defineProps(['item'])
</script>