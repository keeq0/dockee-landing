<template>
    <nav class="navigation">
        <li class="navigation__item">
            <a class="navigation__link" href="#service">Сервис</a>
        </li>
        <li class="navigation__item">
            <a class="navigation__link" href="#service">Подписки</a>
        </li>
        <li class="navigation__item">
            <a class="navigation__link" href="#service">Команда</a>
        </li>
        <li class="navigation__item">
            <a class="navigation__link" href="#service">Контакты</a>
        </li>
    </nav>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .navigation {
        width: 520px;
        height: 45px;
        background: #FFF;
        border: 1px solid #e6e6e6;
        border-radius: 50px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 0 40px;
        position: relative; /* чтобы дочерние элементы не выходили за границы */
        overflow: visible; /* чтобы полоска не обрезалась */
    }

    .navigation__link {
        font-size: 16px;
        font-weight: 500;
        color: #000;
        transition: color .2s;
        position: relative;
        display: inline-block;
        text-decoration: none;
    }

    .navigation__link::after {
        content: '';
        position: absolute;
        bottom: -25px;
        left: 50%;
        transform: translateX(-50%);
        width: 0;
        height: 3px;
        background: #6C67FD;
        border-radius: 50px;
        transition: width .2s ease;
    }

    .navigation__link:hover {
        color: #6C67FD;
    }

    .navigation__link:hover::after {
        width: 100%;
    }
</style>