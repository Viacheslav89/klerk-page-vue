<template>
    <div class="header">
        <div class="header__logo--wrapper">
            <img src="./../../logo/klerk.svg" class="header__logo"></img>
        </div>
        <ul class="header__bread-crumbs--list">
            <li class="header__bread-crumbs--item"><a href="#" class="header__bread-crumbs--link">Хлебные крошки</a></li>
            <img src="./../../logo/arrow.svg" class="header__logo--arrow"></img>
            <li class="header__bread-crumbs--item"><a href="#" class="header__bread-crumbs--link">Хлебные крошки</a></li>
            <img src="./../../logo/arrow.svg" class="header__logo--arrow"></img>
            <li class="header__bread-crumbs--item"><a href="#" class="header__bread-crumbs--link">Хлебные крошки</a></li>
        </ul>
        <h1 class="header__title">Подписки «Клерка»</h1>
        <ul class="header__service--list">
            <li class="header__service--item"><a href="#" class="header__servise--link header__servise--selected">Рассылки</a></li>
            <li class="header__service--item"><a href="#" class="header__servise--link">Соцсети</a></li>
            <li class="header__service--item"><a href="#" class="header__servise--link">Мессенджеры</a></li>
        </ul>
        <AppMain />
    </div>
</template>

<script setup lang="ts">
import AppMain from './AppMain.vue';

</script>

<style scoped lang="scss">

.header {
    width: 1024px;
    margin: 0 auto;
    font-family: 'Roboto', sans-serif;
    // background-color: bisque;


    &__logo--wrapper {
        width: 75px;
        height: 36px;
        margin: 0 auto;
        margin-top: 48px;
    }

    &__bread-crumbs--list {
        padding: 0;
        width: 373px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        margin-top: 24px;
    }

    &__bread-crumbs--item {
        list-style: none;
        font-size: 13px;
    }

    &__bread-crumbs--link {
        color: #999999;
    }

    &__title {
        padding: 0;
        margin: 0;
        text-align: center;
        font-size: 56px;
        margin-top: 24px;
    }

    &__service--list {
        display: flex;
        justify-content: space-between;
        width: 296px;
        margin: 0 auto;
        padding: 0;
        margin-top: 24px;

    }

    &__service--item {
        list-style: none;
        font-size: 16px;
    }

    &__servise--link {
        color: #666666;
        text-decoration: none;
    }

    &__servise--selected {
        color: #5A8CF1;
        border-bottom: 2px solid #5A8CF1;
        padding-bottom: 18px;
    }

}


@media screen and (max-width: 1200px) {
.header {
width: 375px;

    &__title {
        font-size: 32px;
    }

    &__servise--selected {
        padding-bottom: 10px;
    }
}
}

</style>