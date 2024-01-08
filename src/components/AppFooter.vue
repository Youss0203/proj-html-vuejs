<template lang="">
    <section class="upper">
        <div class="column"></div>
        <div class="column"></div>
        <div class="column"></div>
        <div class="column"></div>
        <div class="column"></div>
    </section>
    <section class="contacts">

    </section>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
    section.upper{
        height: 400px;
        display:flex;

        .column{
            width:20%;
            border:solid black 1px;
        }
    }
    section.contacts{
        height: 50px;
        border-top: 1px solid #7e8890;
    }
</style>