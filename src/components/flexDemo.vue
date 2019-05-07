<template>
    <div id="demo">
        <div id="item1">
            item1
            <div id="item1-1">
                item1-1
            </div>
        </div>
        <div id="item2">
            item2
        </div>
    </div>
</template>

<script>
    export default {
        name: "flexDemo"
    }
</script>

<style lang="scss">
    #demo {
        width: 100%;
        height: 100%;
        background-color: antiquewhite;
        color: darkorange;
    }
    #item1 {
        width: 100px;
        height: 50px;
        background-color: #000;
        #item1-1 {
            width: 50px;
            height: 25px;
            background-color: rebeccapurple;
        }
    }
    #item2 {
        width: 100px;
        height: 50px;
        background-color: aqua;
    }
</style>