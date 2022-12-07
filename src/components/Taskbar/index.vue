<template>
<div class="list">
    <div class="list1">
        <div>办件进度</div>
        <a></a>
        <div>办件评价</div>
        <a></a>
        <div>政民互动</div>
        <a></a>
        <div>政务透明</div>
    </div>
    <div class="list2">
        <div class="service">便民服务</div>
        <div class="d1">
            <a style="border-right: 1px solid #1482F1;"><p>普通话证书查询</p></a>
            <a style="border-right: 1px solid #1482F1;"><p>国家科学技术奖查询</p></a>
            <a style="border-right: 1px solid #1482F1;"><p>信用信息查询</p></a>
            <a><p>准营准办</p></a>
        </div>
        <div class="d2">
            <a style="border-right: 1px solid #1482F1;"><p>疫情风险查询</p></a>
            <a style="border-right: 1px solid #1482F1;"><p>核酸检测机构查询</p></a>
            <a style="border-right: 1px solid #1482F1;"><p>核酸检测机构查询</p></a>
            <a><p>社会保障</p></a>
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
    .list1{
        display:flex;
        position: absolute;
        left: 300px;
        top: 450px;
        background-color: #1482F1;
        height: 130px;
    }
    .list1>div{
        display:inline;
        background-color:white;
        opacity: 0.9;
        width: 150px;
        height: 75px;
        font-size: 18px;
        text-align: center;
        line-height: 75px;
        z-index: 1;
        margin: 30px;
        cursor: pointer;
        user-select: none;
    }
    .list1>a{
        width: 20px;
    }
    .list2{
        display: flex;
        position: absolute;
        top: 620px;
        left: 250px;
        background-color: #f4f4f4;
        height: 250px;
        width: 1000px;
    }
    .service{
        background-color: #1482F1;
        height: 200px;
        width: 130px;
        text-align:center;
        line-height: 200px;
        font-size: 20px;
        color: white;
        position: absolute;
        left: 20px;
        top: 28px;
        user-select: none;
    }
    .d1{
        display: flex;
        position: absolute;
        height: 100px;
        width: 800px;
        left: 170px;
        top: 30px;
    }
    .d2{
        display: flex;
        position: absolute;
        height: 100px;
        width: 800px;
        left: 170px;
        top: 130px;
    }
    .d1>a{
        display: flex;
        flex: 1;
        border-bottom:1px solid #1482F1;
        font-size: 20px;
        text-align: right;
    }
    .d2>a{
        display: flex;
        flex: 1;
        font-size: 20px;
    }
    .list p{
        position: relative;
        left: 10px;
        cursor: pointer;
        user-select: none;
    }
</style>