<template>
    <div id="tab-bar">
        <slot></slot>
    </div>
</template>

<script>
export default {
    name:'tabBar',
    components:{

    }
}
</script>

<style scoped>
    #tab-bar{
        display:flex;
        background:#f2f2f2;
        position:fixed;
        bottom:0;
        left:0;
        right:0;
        box-shadow: 0px -2px 2px rgba(100,100,100,0.1);
    }
</style>