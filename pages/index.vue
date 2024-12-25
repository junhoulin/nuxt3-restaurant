<template>
    <div>
        <p>pagepagepagepage</p>
        <NuxtLink to="/menu">关于页面</NuxtLink>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}

 p{
    font-size: 100px;
 }

</style>