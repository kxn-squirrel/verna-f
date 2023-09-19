<template>
<div>
    <p>JSON Format</p>
</div>
<main id="jsonFmain">
    <div class="srcDivWrapper"><textarea id="jsonSrc" class="inputArea"></textarea></div>
    <div id="dragEle"></div>
    <div class="showDivWrapper">
        <div id="jsonRes" class="outputArea"></div>
    </div>
</main>
</template>

<script>
export default {
    data() {

    }
}
</script>

<style>
#jsonFmain {
    background-color: lightgray;
    width: 99%;
    height: 95%;
    position: absolute;
    font-family: menlo, monospace, Tahoma, 微软雅黑, 幼圆 !important;
}

.srcDivWrapper {
    background-color: lightcyan;
    width: 49.5%;
    height: 96.5%;
    padding: 0%;
    position: relative;
    cursor: move;
    Float: left;
}

.inputArea {
    width: 91.5%;
    height: 96.5%;
    padding: 4%;
    border: 1px solid #eee;
    float: inline-start;
    resize: none;
}

#dragEle {
    background-color: red;
    width: 10px;
    height: 96.5%;
    position: relative;
    cursor: move;
    float: left;
}

.showDivWrapper {
    background-color: lightcyan;
    width: 49.5%;
    height: 96.5%;
    padding: 0%;
    position: relative;
    cursor: move;
    Float: left;
}

.outputArea {
    background-color: lightpink;
    width: 91.5%;
    height: 96.5%;
    padding: 4%;
    border: 1px solid #eee;
    position: relative;
    float: inline-start;
}

.inputPadding {
    line-height: 100%;
    font-family: menlo, monospace, Tahoma, 微软雅黑, 幼圆;
}
</style>
