<template>
<div id="Home">
    <Lunbotu class="lunbotu"></Lunbotu>
    <Tongyi class="tongyi"></Tongyi>
    <Taskbar class="taskbar"></Taskbar>
</div>
</template>

<script>
import Lunbotu from '../../components/Lunbotu'
import Tongyi from '../../components/Tongyi'
import Taskbar from '../../components/Taskbar'

export default {
    name: 'Home',
    components: {
        Lunbotu,
        Tongyi,
        Taskbar
    }

}
</script>

<style scoped>
    #Home{
        position: relative;
        margin-left: auto;
        margin-right: auto;
        width: 1540px;
        height: 1000px;
    }
    .lunbotu{
    }
    .tongyi{
        position: absolute;
        top:20px;
        z-index: 99;
    }
    .taskbar{
        position: absolute;
        top:300;
        z-index: 99;
    }
</style>