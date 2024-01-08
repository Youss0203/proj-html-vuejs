<template lang="">
    <section class="contacts"></section>
    <section class="navigation"></section>
    <section class="jumbo"></section>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
@use "../../src/styles/partials/mixins.scss" as*;
@use "../../src/styles/partials/variables.scss" as*;
    section.contacts{
        height: 30px;
        background-color: #f09a3e;
    }
    section.navigation{
        height: 100px;
        background-color: blueviolet;
    }

    section.jumbo{
        height:500px;
        background-color: aqua;
    }
</style>