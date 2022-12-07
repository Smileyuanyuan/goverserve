<template>
<div id="Progress">
    <div class="picture">
        <a>办理进度</a>
    </div>
    <div class="background">
        <div class="navigation">
            <div class="mydocu">我的办理业务</div>
        </div>
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
    .picture{
        height: 300px;
        width: 1540px;
        background-color: #6db6ff;
    }
    .picture>a{
        position: absolute;
        top:200px;
        left: 100px;
        font-size: 30px;
        color: white;
        
    }
    .background{
        border: 1px solid rgb(190, 189, 189);
        position: relative;
        top: -120px;
        left: 170px;
        width: 1200px;
        height: 500px;
        background-color: white;
        box-shadow: 2px 2px 2px 2px #c7c7c7;
    }
    .navigation{
        border: 1px solid rgb(174, 174, 174);
        position: relative;
        height: 500px;
        width: 200px;
    }
    .mydocu{
        position: relative;
        top: 50px;
        width: 150px;
        left: 20px;
        font-size: 20px;
    }
</style>