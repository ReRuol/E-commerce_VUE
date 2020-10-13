<template>
    <div class="page">
        <div class='content' v-html="$store.state.goods.details.bodys"></div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
    .page{margin-top:1.2rem;}
    .content{width:85%;height: 35%;margin:0 auto;font-size:0.32rem;line-height:0.5rem;background-color: #fff;border-radius: 10px;padding: 0.4rem}
</style>
