<template>
<div class="list">
    <div class="list1">
        <div><img src="@/assets/identify.png" style="position: relative;top: 10px;width: 35px;">统一身份认证</div>
        <a></a>
        <div><img src="@/assets/dealevent.png" style="position: relative;top: 10px;width: 35px;">统一事项办理</div>
        <a></a>
        <div><img src="@/assets/evaluate.png" style="position: relative;top: 10px;width: 35px;">统一好评差评</div>
        <a></a>
        <div><img src="@/assets/serve.png" style="position: relative;top: 10px;width: 35px;">统一用户服务</div>
    </div>
</div>
</template>

<script>
export default {
    data(){
        return {
        };    
    },
methods: {},
};
</script>

<style scoped>
    .list1{
        display:flex;
        position: absolute;
        left: 300px;
        top: 280px;
    }
    .list1>div{
        display:inline;
        background: rgb(255, 255, 255);
        opacity: 0.7;
        width: 150px;
        height: 75px;
        font-size: 18px;
        text-align: center;
        line-height: 75px;
        z-index: 1;
        cursor: pointer;
        user-select: none;
    }
    .list1>a{
        width: 100px;
    }
</style>