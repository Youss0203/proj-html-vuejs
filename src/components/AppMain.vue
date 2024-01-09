<template lang="">
    <section class="university">
        <div class="container">
            <div class="content-logo">
                <img src="../../src/images/page-logo-1.png" alt="logo Avada">
                <h1>Inspired By Excellence & Innovation</h1>
                <p>We offer a wide range of high quality of teaching and extra-curricular activites.</p>
            </div>
            <div class="divider"></div>
            <div class="content">
            <div class="column">
                <h1 class="small">WHY CHOOSE AVADA UNIVERSITY?</h1>
                <p>We offer a range of training packages in a range of subject areas and can offer blended learning. opportunities to best meet your needs. If sitting in a room with a trainer and having the opportunity for discussion with ether learners sounds good to you then we can offer this. 
                   If you prefer to study in your own time and at your own speed then one of our worldl class facilities.
                </p>
                <p>"you pecter to study i your own time and at your own speed then the of our clearning packages may be right up your street. 
                There is a third option, which is you like the sound of both but perhaps cart okend all training sessions, this is when blended learning cornes into its own.
                </p>
            </div>
            <div class="columns">
                <img class="image-content" src="../../src/images/fss-demo-main.jpg" alt="">
            </div>
        </div>
        </div>
    </section>
    <section class="values">
        <div class="container d-flex">
            <div class="col-50">
                <h1>WORLD CLASS FACILITIES</h1>
                <p>Avada University is devoted to excellence in teaching, learning, and research, and developing leaders in many disciplines who make a difference globally.</p>
                <ul>
                    <li><i class="fa-solid fa-globe"></i><span> International focus</span> - our students come from across the globe</li>
                    <li><i class="fa-solid fa-graduation-cap"></i><span>Residential courses</span> - we encourage learning and growth</li>
                    <li><i class="fa-regular fa-address-book"></i><span> People not profits</span> - education is a right not a privilege</li>
                </ul>
                <p>If you prefer to study in your own time and at your own speed then one of our e-
                   learning packages may he right up your street.</p>
            </div>
            <div class="col-50">
                <h1>OUR VALUES</h1>
                <div class="square">  
                    <p><i class="fa-solid fa-plus"></i>OUR MISSION</p>
                </div>
                <div class="square">  
                    <p><i class="fa-solid fa-plus"></i>OUR PHILOSOPHY</p>
                </div>
                <div class="square">  
                    <p><i class="fa-solid fa-plus"></i>OUR COMMITTENT</p>
                </div>
                <div class="square">  
                    <p><i class="fa-solid fa-plus"></i>OUR PROMISE</p>
                </div>
                <div class="square">  
                    <p><i class="fa-solid fa-plus"></i>OUR VALUES</p>
                </div>
            </div>
        </div>
    </section>
    <section class="boxes">
        <div class="box box-1">
            <h1>COURSES</h1>
            <div class="divider"></div>
            <p>View more</p>
        </div>
        <div class="box box-2">
            <h1>EVENTS</h1>
            <div class="divider"></div>
            <p>View more</p>
        </div>
        <div class="box box-3">
            <h1>LATEST NEWS</h1>
            <div class="divider"></div>
            <p>View more</p>
        </div>
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

        margin-bottom:7rem;
        div.content-logo{
            text-align: center;

            h1{
                margin-bottom:.5rem;
            }
        
            p{
            color:#7e8890;
            margin-bottom: 1rem;
            }

        }
        .small{
            font-size:15px;
            margin-bottom:.5rem
        }
        .column{
            width: 55%;
        }
        p{
            font-size:13px;
            line-height: 20px;
            color:#7e8890;
            margin-bottom:1rem;
        }
        .columns{
            width:calc(100% - 55%);
            margin-left:5rem;
        }
        
        .content{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .image-content{
            width: 80%;
        }
    }
    section.values{
        height: 300px;
        

        p{
            color:#7e8890;
            font-size:13px;
            margin-bottom:2rem;
            padding-right:1.3rem;
        }

        .col-50{
            width: 50%;
        }
        h1{
            font-size:15px;
            margin-bottom:1rem;
        }
        ul{
            list-style-type: none;

            li{
                color:#7e8890;
                font-size:13px;
            }
            span{
                font-weight: bold;
                color:black
            }
            i{
                color:#e58925;
                padding-right:.5rem;
                margin-bottom: 1.5rem;
            }
        }

        .square{
            background-color: white;
            padding:.5rem 5rem 1.5rem 1rem;
            height:20px;
            border:1px solid;
            margin-bottom:1rem;

            p{
                color:#e58925;
                font-size:18px;
                font-weight: bold;
            }
            i{
                color:#e58925;
                font-weight: bold;
                padding-right:1rem;
            }
        }
    }

    section.boxes{
        display: flex;
        div.box{
        width: calc(100% / 3);
        height: 400px;
        border: solid 1px black;
        }
        .box-1{
            background-image: url(../../src/images/home_courses_section_bg.jpg);
            background-size: 100%;
        }
        .box-2{
            background-image: url(../../src/images/home_events_section_bg.jpg);
            background-size: 100%;
        }
        .box-3{
            background-image:url(../../src/images/home_latest_news_section_bg.jpg) ;
            background-size: 100%;
        }
        h1{
            text-align: center;
            margin-bottom: 1rem;
            color:white;
            padding-top:11rem;
        }
        p{
            text-align: center;
            color:white;
        }
        .divider{
        margin-bottom:1rem;
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
    .divider{
        width: 14%;
        background-color: #e58925;
        height: 1px;
        margin: 0 auto;
        margin-bottom:2rem;
    }

    .d-flex{
        display: flex;
    }
</style>