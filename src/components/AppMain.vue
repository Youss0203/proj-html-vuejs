<template lang="">
    <section class="university">
        <div class="container"></div>
    </section>
    <section class="values">
        <div class="container"></div>
    </section>
    <section class="boxes">
        <div class="box"></div>
        <div class="box"></div>
        <div class="box"></div>
    </section>
    <section class="news">
        <div class="container"></div>
    </section>
    <section class="newsletter">
        <div class="container"></div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
    .container{
        height: 100%;
        width: 60%;
        margin:0 auto;
        border: solid black 1px;
    }
    section.university{
        height: 400px;
        background-color: aquamarine;
    }
    section.values{
        height: 300px;
        background-color: red;
    }

    section.boxes{
        display: flex;
        div.box{
        width: calc(100% / 3);
        height: 300px;
        border: solid 1px black;
        }
    }

    section.news{
        height: 400px;
        background-color: yellow;
    }

    section.newsletter{
        height: 200px;
        background-color: #333c4e;
    }
</style>