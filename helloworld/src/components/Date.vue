<template>
    <div class="calender">
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
        <div>6</div>
        <div>7</div>
        <div>8</div>
        <div>9</div>
        <div>10</div>
    </div>
</template>
<script>
export default {
    name: 'Date',
    props: {

    },
    data: function(){
        return {

        }
    }
}
</script>
<style lang="scss" scoped>
.calender {
    width: 500px;
    &:after {
        clear: both;
        display: block;
        content: "";
    }
    ::v-deep div {
        float: left;
        width: 100px;
        height: 100px;
        font-weight: bold;
        font-size: 20px;
        text-align: center;
        line-height: 100px;
        border: 1px solid #000;
        box-sizing: border-box;
        &.active {
            background: #0bf;
        }
    }
}
</style>