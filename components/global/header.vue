<template>
    <div class="header">
        <div class="h-item"><a href="/">我的菜單</a></div>
        <div class="h-item"><a href="/menu">我的菜單</a></div>
        <div class="h-item"><a>我的菜單</a></div>
        <div class="h-item"><a>我的菜單</a></div>
        <div class="h-item"><a>我的菜單</a></div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

.header {
    margin: 0;
    width: 100%;
    height: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #1D1D1D;
}

.h-item {
    padding: 16px 16px;
    border-right: solid 1px rgb(250, 246, 238);
    &:last-child {
        border-right: none;
    }
    a {
        color: #E0CA8F;
        padding: 16px 16px;
        line-height: 1.2;
        letter-spacing: 0.3em;
        transition: all 0.5s ease;
        &:hover{
            color: #1D1D1D;
            cursor: pointer;
            background-color: #E0CA8F;
        }
    }
}

</style>