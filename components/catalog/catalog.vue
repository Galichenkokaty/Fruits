<template>
    <div class="catalog">
        <h2 class="catalog__title">oRGANIC fRUITS</h2>
        <div class="catalog__sub-title">Our organic fruits are hand-picked from local farms and delivered straight to your doorstep, ensuring that you get the freshest and most nutritious produce possible. We offer a wide selection of organic fruits grown without the use of harmful pesticides or chemicals.</div>
        <div class="catalog__items">
            <CatalogItem v-for="(item, index) in items" :key="index" :item="item"></CatalogItem>
        </div>
        <div class="catalog__order-btn">
            <div class="catalog__order-btn-arrow">
            </div>
            <p class="catalog__order-btn-text">oRDER</p>
        </div>
    </div>
</template>
<script setup>
    import '~/components/catalog/__catalog.css'
    const items = ref([
        {
            name:'Strawberry',
            img:'catalog/catalog__item-img-1.png',
            price:'100 UAH / kg',
            color:'F8766B'
        },
        {
            name:'Banana',
            img:'catalog/catalog__item-img-2.png',
            price:'80 UAH / kg',
            color:'EDD251'
        },
        {
            name:'Watermelon',
            img:'catalog/catalog__item-img-3.png',
            price:'40 UAH / kg',
            color:'9DC262'
        },
        {
            name:'Lime',
            img:'catalog/catalog__item-img-4.png',
            price:'60 UAH / kg',
            color:'BFD663'
        },
        {
            name:'Apple',
            img:'catalog/catalog__item-img-5.png',
            price:'50 UAH / kg',
            color:'E93F29'
        },
        {
            name:'Peach',
            img:'catalog/catalog__item-img-6.png',
            price:'80 UAH / kg',
            color:'DB4F4B'
        },
        {
            name:'Plums',
            img:'catalog/catalog__item-img-7.png',
            price:'40 UAH / kg',
            color:'9B5366'
        },
        {
            name:'Orange',
            img:'catalog/catalog__item-img-8.png',
            price:'60 UAH / kg',
            color:'F47F4C'
        },
        {
            name:'Kiwi',
            img:'catalog/catalog__item-img-9.png',
            price:'90 UAH / kg',
            color:'98B37E'
        },
    ])
</script>
