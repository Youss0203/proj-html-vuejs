<template lang="">
    <section class="contacts">
        <div class="container d-flex-between">
            <ul>
                <li><i class="fa-solid fa-phone-flip"></i> <p>1.800.567.8910</p> <p class="small">24hrs</p></li>
                <li><i class="fa-solid fa-envelope"></i> <p>Contact Us</p></li>
                <li><i class="fa-solid fa-graduation-cap"></i> <p>Alumni</p></li>
                <li><i class="fa-solid fa-landmark"></i> <p>Campus</p></li>
            </ul>
            <ul>
                <li><i class="fa-brands fa-facebook-f"></i></li>
                <li><i class="fa-brands fa-twitter"></i></li>
                <li><i class="fa-brands fa-youtube"></i></li>
                <li><i class="fa-brands fa-instagram"></i></li>
            </ul>
        </div>
    </section>
    <section class="navigation">
        <div class="container d-flex-between">
            <div class="logo">
                <img src="../../src/images/university_logo.png" alt="logo Avada">
            </div>
            <div class="nav">
                <ul>
                <li v-for="link in listLink">
                    {{link.content}}
                </li>
                </ul>
            </div>
        </div>
    </section>
    <section class="jumbo">
        <div class="jumbo-title">
            <h1>Inspiring Tomorrows Leaders</h1>
            <h3>The Future Belong To Thoose Who See Possibilities Today</h3>
        <div class="btn">
            <button class="btn-orange">FIND A COURSE</button>
            <button class="btn-blue">APPLY NOW</button>
        </div>
    </div>

    </section>
</template>
<script>
export default {
    data() {
        return {
            listLink:[
                {
                    content:"HOME",
                    url:"#"
                },
                {
                    content:"ABOUT",
                    url:"#"
                },
                {
                    content:"COURSES",
                    url:"#"
                },
                {
                    content:"EVENTS",
                    url:"#"
                },
                {
                    content:"FACILITIES",
                    url:"#"
                },
                {
                    content:"NEWS",
                    url:"#"
                },
                {
                    content:"ADMISSION",
                    url:"#"
                },
               
            ]
        }
    },
}
</script>
<style lang="scss" scoped>
@use "../../src/styles/partials/mixins.scss" as*;
@use "../../src/styles/partials/variables.scss" as*;
    section.contacts{
        background-color: #f09a3e;


            i,p{
                color:white;
                padding:.3rem;
                font-size:12px;
            }

            p.small{
                font-size:8px;
                background-color: #E58925;
                border-radius: 10%;
                padding:.07rem;
            }

            
        
    }
    ul{
            list-style-type: none;
            display: flex;
            align-items: center;
        }
        li{
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 0 .4rem;}
    section.navigation{

        padding:.5rem 0;
        li{
            font-size:13px;
            font-weight: bold;
        }

        li:hover{
            color:#E58925
        }
    }

    section.jumbo{
        height:700px;
        background-image: url(../../src//images/home_main_slider_bg.jpg);
        background-position: center;
        display: flex;
        justify-content: center;
        align-items: center;

        .jumbo-title{
            text-align: center;
        }
        h1{
           color:white;
            font-size:50px;
        }
        h3{
            color:white;
            margin-bottom:1rem;
        }
        button{
            border:none;
            padding:.5rem;
            margin:0 .5rem;
            color:white;
        }

        .btn-orange{
            background-color: #E58925;
        }
        .btn-blue{
            background-color: #00bcd4;
        }
    }

    .container{
            height: 100%;
            width: 60%;
            margin: 0 auto;
        }
    .d-flex-between{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }    

</style>