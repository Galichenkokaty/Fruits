<template>
    <div class="order">
        <h2 class="order__title"> Fresh Harvest Box has<br> got you covered</h2>
        <div class="order__images">
            <div class="order__image">
                <NuxtPicture class="thumb" src="order/image-1.jpg" />
            </div>
            <div class="order__image">
                <NuxtPicture class="thumb" src="order/image-2.jpg" />
            </div>
        </div>
        <div class="order__mail">
            <div class="order__mail-text">Our boxes are packed with delicious, nutritious fruits and vegetables, perfect for anyone looking to eat healthier or support local farmers. Order your box today and start enjoying the best that nature has to offer!</div>
            <div class="order__mail-form">
                <input class="order__mail-form-input" placeholder="Enter email">
                <button class="order__mail-form-btn">Send</button>
            </div>
        </div>
    </div>
</template>
<script setup>
    import '~/components/order/__order.css'
</script>