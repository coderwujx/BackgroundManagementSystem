<script setup lang="ts">
import LoginFrom from './components/login/LoginFrom.vue'


</script>

<template>
    <div class="login">
        <login-from />
    </div>
</template>

<style lang="less" scoped>
.login {
    height: 100vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url('../assets/img/login-bg.svg');
}
</style>