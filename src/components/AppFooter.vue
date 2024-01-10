<template lang="">
    <section class="upper">
        <div class="column">
            <h1>AVADA UNIVERSITY</h1>
            <ul>
                <li><i class="fa-solid fa-house"></i><p>Residential location 9521 Brodsberry Avenue Paddington RC7 92A</p></li>
                <li><i class="fa-solid fa-phone-flip"></i><p>1.800.458.556</p></li>
                <li><i class="fa-regular fa-envelope"></i><p>info@your-domain.com</p></li>
                <li><i class="fa-regular fa-clock"></i> <p>Monday - Friday: 8.00AM - 10PM</p></li>
            </ul>
        </div>
        <div class="column">
            <h1 class="padding-t">RECENTS POSTS</h1>
            <h2>>What do successful grads think you should study?</h2>
            <p class="padding">March 16, 2016</p>  
            <div class="divider"></div>

            <h2>> Former student discusses success in the fashion industry</h2>
            <p class="padding">March 15, 2016</p>  
            <div class="divider"></div>

            <h2>>How do you best prepare for university?</h2>
            <p class="padding">March 15, 2016</p>  
            <div class="divider"></div>
        </div>
        <div class="column">
            <h1>COURSES</h1>
            <ul>
                <li v-for="link in linkitems"><p>{{link.content}}</p></li>
            </ul>
            <h1>ADMISSION</h1>
            <ul>
                <li v-for="link in links"><p>{{link.content}}</p></li>
            </ul>
        </div>
        <div class="column">
            <h1>RESOURCES</h1>
            <ul>
                <li v-for="link in resources"><p>{{link.content}}</p></li>
            </ul>
            <h1>QUICKLINKS</h1>
            <ul>
                <li v-for="link in quicklinks"><p>{{link.content}}</p></li>
            </ul>
        </div>
        <div class="column">
            <h1>UPCOMING EVENTS</h1>
            <div class="d-flex">
            <div>
            <img class="calendar" src="../../src/images/calendar.jpg" alt="">
            </div>
            <div>
            <h1 class="business">Business seminar</h1>
            <p class="business-content">July 1, 2019 @ 8:00 am - July 1, 2021 @ 5:00 <br> pm <br> United States</p>
            </div>
            </div>

            <div class="business-divider"></div>

            <h1>UPCOMING EVENTS</h1>
            <div class="d-flex">
            <div>
            <img class="calendar" src="../../src/images/calendar.jpg" alt="">
            </div>
            <div>
            <h1 class="business">Politics seminar</h1>
            <p class="business-content">November 5, 2019 @ 800 am - November 6, 2021 © 5:00 pm Unted Kingdom pm <br> United States</p>
            </div>
            </div>
            <div class="business-divider"></div>
            <p class="padding">View more ...</p>
        </div>
    </section>
    <section class="contacts">

    </section>
</template>
<script>
export default {
    data() {
        return {
            linkitems: [
                {
                    content: "Arts & Humanities",
                    url: "#"
                },
                {
                    content: "Business & Management",
                    url: "#"
                },
                {
                    content: "Engineering & Technology",
                    url: "#"
                },
                {
                    content: "Life Sciences & Medicine",
                    url: "#"
                },
                {
                    content: "Natural Sciences",
                    url: "#"
                },

            ],
            links: [
                {
                    content: "Eligibility",
                    url: "#"
                },
                {
                    content: "Application",
                    url: "#"
                },
                {
                    content: "Reviw Process",
                    url: "#"
                },
                {
                    content: "How to Apply",
                    url: "#"
                },

            ],
            resources: [
                {
                    content: "Campus Directory",
                    url: "#"
                },
                {
                    content: "Academic Calendary",
                    url: "#"
                },
                {
                    content: "Sports Clubs",
                    url: "#"
                },
                {
                    content: "Graduate Programs",
                    url: "#"
                },
                {
                    content: "Faculty & Staff",
                    url: "#"
                },
            ],
            quicklinks: [
                {
                    content: "Univerity Library",
                    url: "#"
                },
                {
                    content: "Campus Services ",
                    url: "#"
                },
                {
                    content: "Carrers",
                    url: "#"
                },
            ]
        }
    },
}
</script>
<style lang="scss">
section.upper {
    display: flex;
    background-image: url(../../src/images/university_ft_bg.png);
    background-size: 100%;

    .column {
        width: 20%;
    }

    h1 {
        font-size: 15px;
        padding: 0 3rem;
        margin-bottom: 1rem;
        padding-top: 4rem;
    }

    h2 {
        font-size: 15px;
        padding: 0 2rem;
        margin-bottom: 1rem;
        padding-top: 1rem;
    }

    p {
        color: #7e8890;
        font-size: 13px;

    }

    li {
        display: flex;
        padding: 0 3rem;
        margin-bottom: 1rem;


        i {
            color: #e58925;
            margin-right: .5rem;
        }

    }

    .padding {
        padding: 0 2rem;
    }

    .padding-t {
        padding: 4rem 2rem 0;
    }

    .divider {
        height: 1px;
        width: 80%;
        background-color: #7e8890;
        margin: 0 auto;
        margin-top: .5rem;
    }

    .calendar {
        width: 50px;
        height: 70px;
        margin-left: 2rem;
    }

    .d-flex {
        display: flex;
    }
    .business{
        
        
        font-size: 15px;
        margin-bottom: 1rem;
        padding-top: 0;
        padding-left: 1rem;
    }
    .business-content{
        font-size: 12px;
        margin-bottom: 1rem;
        padding-top: 0;
        padding-left: 1rem;
    }
    .business-divider{
        height: 1px;
        width: 80%;
        background-color: #7e8890;
        margin: 0 auto;
        margin-top: .5rem;
    }


}

section.contacts {
    height: 50px;
    border-top: 1px solid #7e8890;
}</style>