<template>
    <div class="inputs flex">
        <input type="text">
        <div class="x_btn">&times;</div>
    </div>
</template>

<style lang="scss" scoped>
div.inputs{
    max-width: 767px;
    border: 1px solid #d0d0d0;
        padding: 10px;
    input{
        flex: 1;
        border: 0;
        outline: none;
    }
    div.x_btn{
        width: 5%;
        font-size: 25px;
    }
}
</style>