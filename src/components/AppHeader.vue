<template lang="">
    <section class="contacts">
        <div class=container></div>
    </section>
    <section class="navigation">
        <div class=container></div>
    </section>
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

    .container{
            height: 100%;
            width: 60%;
            margin: 0 auto;
            border: solid black 1px;
        }

</style>