<template>
    <div class="header">
        <div class="header__image-bg --banana">
            <NuxtPicture class="thumb" src="header/banana.png" />
        </div>
        <div class="header__image-bg --strawberry">
            <NuxtPicture class="thumb" src="header/strawberry.png" />
        </div>
        <h1 class="header__title">fresh harvest box<br> is your one-stop place for a delicious fruit basket</h1>
        <div class="header__items">
            <div class="header__item">
                <div class="header__item-content">
                    <div class="header__item-content-text">
                        Our expertly curated fruit baskets are made with the freshest, highest quality fruits available. Whether you are looking for a healthy snack or a gift for a loved one, Fresh Harvest Box has got you covered.
                    </div>
                    <div class="header__item-content-fruit --green">
                        <p class="header__item-content-fruit-title">Fruit</p>
                        <div class="header__item-img">
                            <NuxtPicture class="thumb" src="header/header__img-item-1.png" />
                        </div>
                        <p class="header__item-content-fruit-text">
                            Refreshing and juicy, watermelon is the perfect summer treat and a great source of hydration
                        </p>
                    </div>
                </div>
            </div>
            <div class="header__item">
                <div class="header__item-img">
                    <NuxtPicture class="thumb" src="header/header__img-item-2.jpg" />
                <div class="header__item-btn">shop<br>now</div>
                </div>
            </div>
            <div class="header__item">
                <div class="header__item-content">
                    <div class="header__item-content-fruit --yellow">
                        <p class="header__item-content-fruit-title">Fruit</p>
                        <div class="header__item-img">
                            <NuxtPicture class="thumb" src="header/header__img-item-3.png" />
                        </div>
                        <p class="header__item-content-fruit-text">Sweet and juicy, strawberries are packed with vitamin C and antioxidants, making them a delicious and healthy snack</p>
                    </div>
                    <div class="header__item-content-tags">
                        <div class="header__item-content-tag">#organic</div>
                        <div class="header__item-content-tag">#products</div>
                        <div class="header__item-content-tag">#basket</div>
                        <div class="header__item-content-tag">#fruits</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script setup>
    import '~/components/header/__header.css'
</script>