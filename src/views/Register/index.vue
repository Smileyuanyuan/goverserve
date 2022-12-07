<template>
<div class="register_page">
    <div style="color:#1482F1;">立即注册</div>
    <div style="height:20px;"></div>
    <el-input v-model="in_email" placeholder="邮箱"></el-input>
    <div style="height:20px;"></div>
    <el-input placeholder="验证码" v-model="in_captcha" class="captcha"></el-input>     
    <div style="height:20px;"></div>
    <el-input placeholder="设置密码" v-model="in_passwd" show-password ></el-input>
    <div style="height:20px;"></div>
    <el-input placeholder="确认密码" v-model="in_passwd1" show-password ></el-input>
    <div style="height:20px;"></div>
    <div class="submit">确认</div>  
</div>
</template>

<script>
export default {
    data(){
        return {
            in_email: '', 
            in_captcha:'',
            in_passwd: '',
            in_passwd1: '',
        };
    },
mounted() {
    document.querySelector('body').setAttribute('style', "background-color:#D8EBFF;")
  },
beforeDestroy() {
   document.querySelector('body').removeAttribute('style')
  },

};
</script>

<style scoped>
    .register_page{
        float: center;
        width:200px;
        position: absolute;
        left: 39%;
        top: 30%;
    }
    .captcha{
    }
    .submit{
        background-color: #1482F1;
        color: white;
        position: relative;
        left: 70px;
        width: 60px;
        height: 30px;
        line-height: 30px;
    }
</style>
