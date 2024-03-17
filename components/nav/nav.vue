<template>
    <div class="nav">
        <div class="nav__items">
            <div class="nav__item">How It Works</div>
            <div class="nav__item">Fruits</div>
            <div class="nav__item">Contacts</div>
        </div>
        <div class="nav__logo">
            <NuxtIcon class="nav__logo-img thumb" name="logo" filled />
        </div>
        <div class="nav__basket">
            <NuxtIcon class="nav__basket-img thumb" name="basket" filled />
        </div>
    </div>
</template>
<script setup>
    import '~/components/nav/__nav.css'
</script>