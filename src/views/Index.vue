<template>
    <div class='index'>首页</div>
    <el-button @click="goLogin">前去登录</el-button>
</template>

<script> 
import router from '../router/index'

export default {
    name: 'Index',
    // github webhook 测试
    components: {},
    setup(){
        const goLogin = ()=>{
            router.push('/login')
        }

        return {goLogin}
    }
};
</script>

<style lang="">
    
</style>