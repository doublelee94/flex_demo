<template>
    <div id="demo">
        <div id="item1">
            item1
            <br>
            l1
            <!--<div id="item1-1">-->
                <!--item1-1-->
            <!--</div>-->
        </div>
        <div id="item2">
            item2
            <br>
            l2
            <br>
            l2
        </div>
        <div id="item3">
            item3
            <br>
            l3
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
        </div>
        <div class="item">
            item
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
        color: black;
        display: flex;
        /*flex-direction: row;*/
        /*flex-wrap: wrap-reverse;*/
        flex-flow: row-reverse wrap;
        justify-content: space-around;
        align-items: flex-start;
        align-content: center;
    }
    #item1 {
        width: 700px;
        height: 30px;
        background-color: pink;
        flex-shrink: 1;
        order: 5;
        flex-grow: 5;
        /*flex-basis: 500px;*/
        align-self: center;
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
        flex-grow: 1;
        order: 6;
    }
    #item3 {
        width: 100px;
        height: 30px;
        background-color: red;
        flex-grow: 1;
        order: 7;
    }
    .item {
        width: 10%;
        height: 100px;
        background-color: greenyellow;
        flex-grow: 1;
        order: 2;
    }
</style>