<template>
    <div>
        <ul class="menu">
            <li class="menu-item">
                <router-link to="/">首页</router-link>
            </li>
            <li class="menu-item">
                <router-link to="/category">分类</router-link>
            </li>
            <li class="menu-item">
                <router-link to="/cart">购物车</router-link>
            </li>
            <li class="menu-item">
                <router-link to="/profile">我的</router-link>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.menu{
    display: flex;
    position: fixed;
    bottom: 0;
    width: 100%;
    &-item{
        flex-grow: 1;
        text-align: center;
        height: 1rem;
        line-height: 1rem;
        background: #cccccc;
    }
}
</style>