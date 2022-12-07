<template>
<div class="header1">
<el-menu
  :default-active="activeIndex2"
  class="el-menu-demo"
  mode="horizontal"
  @select="handleSelect"
  background-color="#fff"
  text-color="black"
  active-text-color="#1482F1">
  <img src="@/assets/headlogo.png" border="none" style="max-width:none; float:left;">
  <el-menu-item index="1" label="首页" @click="handleClick(1)">首页</el-menu-item>
  <el-menu-item index="2" labe="个人服务" @click="handleClick(2)">个人服务</el-menu-item>
  <el-menu-item index="3" label="办理套餐" @click="handleClick(3)" >办理套餐</el-menu-item>
  <!-- <el-menu-item index="4"><a  target="_blank">登录</a></el-menu-item> -->
  <!-- <el-menu-item index="5"><a  target="_blank">注册</a></el-menu-item> -->
</el-menu>
  <div class="login">
      <div><a>登录</a></div>
      <div><a class="register" @click="toregister">注册</a></div>
  </div>
<div class="nav">
    当前位置：{{navigation}}
</div>
</div>
</template>

<script>
  export default {
    data() {
      return {
        navigation: '首页',
        str:['首页','个人服务','办理套餐'],
        activeIndex: '1',
        activeIndex2: '1'
      };
    },
    methods: {
        handleSelect(key, keyPath) {
            // console.log(key, keyPath);
        },
        handleClick (idx) {
            // console.log(this.str[idx - 1])
            this.navigation=this.str[idx-1]
      },
      toregister() {
        var self = this;
          console.log("register")
          self.$router.push({name:'register'})
        }
    }
  }
</script>

<style scoped>
    .header1{
      height: 100px;
    }
    .el-menu-item{
      font-size: 20px!important;
    }
    .login{
        width: 100px;
        position: relative;
        top: -40px;
        left: 1400px;
        display: flex;
    }
    .login > div {
        cursor: pointer;
        margin-left: 10px;
    }
    .register{
        width: 50px;
        border-left: 2px solid #1482F1;
        padding-left: 10px;
    }
    .nav{
        position: relative;
        top: -16px;
        float: left;
        font-size: 18px;
    }

</style>
