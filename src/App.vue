<template>
    <div id="app">
        <router-view></router-view>
    </div>
</template>
<script>

    export default {
        name: 'app',
        components: {}
    }
</script>

<style>
    #app {
        font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
        text-align: center;
        color: #2c3e50;
    }

    html, body {
        width: 100vw;
        height: 100vh;
        font-size: 14px;
        padding: 0;
        margin: 0;
    }
</style>
