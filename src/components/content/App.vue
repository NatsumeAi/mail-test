<template>
    <tabbar>
        <tabbaritem></tabbaritem>
        <tabbaritem></tabbaritem>
        <tabbaritem></tabbaritem>
        <tabbaritem></tabbaritem>
    </tabbar>
</template>

<script>
export default {
    name :'App',
    components:{
        tabbar,
        tabbaritem
    }
}

import tabbaritem from '../common/tabbar/tabBarItem';
import tabbar from '../common/tabbar/tabBar';
</script>

<style>
</style>