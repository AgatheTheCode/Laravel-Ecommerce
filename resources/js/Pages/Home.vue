<script setup>

import {Head} from "@inertiajs/vue3";
import SectionTitle from "@/Components/SectionTitle.vue";
import NavigationMain from "@/Components/NavigationMain.vue";
</script>

<template>
    <Head title="Home"/>
    <div>
        <h1>Home</h1>
    </div>
    <NavigationMain/>

    <SectionTitle title="Home" description="lorem  ipsum" aside="aside">
    </SectionTitle>
</template>

<style scoped>
html{
    background-color: #fde496;
}

</style>
