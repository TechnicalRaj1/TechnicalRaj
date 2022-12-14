<html>
    <head>
        <meta name="description" content="Official Raj">
        <meta name="viewport" content="with-device-width,initial-scale=1.0">
        
        <meta name="author" content="Technical Raj" /><title>

        </title>
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body background ="https://www.careerindia.com/img/2022/04/earth-day-640-1651295234.jpg">
        <section class="header">
            <nav>
                
                <div class="nav-links" id="navLinks">
                    <i class="fa fa-times" onclick="hideMenu()"></i>
                    <ul >
                        <li >
                            <p> <a href="https://www.lotuspetalfoundation.org/">HOME</a></p>
                        </li>
                        <li>
                           <p> <a href="">ABOUT US </a></p>
                        </li >
                        <li >
                        <p>    <a href="mailto:godrajgamer83@gmail.com">CONTACT US</a></p>
                        </li>
                    </ul>
                  
                </div>
                <i class="fa fa-bars" onclick="showMenu()"></i>
            </nav>

            <div class="text-box">
                <h1>
                    how are you
                </h1>
                <p>
                    hASGdjhjhdaujhdjvcjajhdjhasgkasjdjhaskahdayasiasdlshdfi
                </p>
                
                <a href="https://youtube.com" class="hero-btn" ><b>Visit us to know more</b></a>
           
            </div>
        </section>
        p {
            text-shadow: 2px 4px 4px royalblue;
        }
    
    *{
        margin:0;
        padding:0;
    }
    .header{
        min-height:100%;
        width:100%;
        background-image: linear-gradient(rgba(255, 1, 1, 0.7)),url("images/download.jfif" );
        background-position: center;
        background-size:cover;
        position:relative;
    }
    
    
    nav{
        display:flex;
        padding:2% 6%;
        justify-content:space-between;
        align-items:center;
    }
    
    
    
    
    
    
    nav img{
        width:150px;
    }
    
    
    
    
    
    .nav-links{
        flex:1;
        text-align:right;
    }
    
    
    
    
    
    .nav-links ul li{
        list-style:none;
        display:inline-block;
        padding:8px 12px;
        position:relative;
    
    }
    
    
    
    
    .nav-links ul li a{
        color:rgb(0, 0, 0);
        text-decoration:none;
        font-size:13px;
        font-family:Arial, Helvetica, sans-serif;
    }
    
    
    
    
    .nav-links ul li::after{
    content:"";
    width:0%;
    height:2px;
    background:#f34f4f;
    display:block;
    margin:auto;
    transition:0.5s;
    }
    
    
    
    
    .nav-links ul li:hover::after{
        width:100%;
        
    }
    
    
    
    
    .text-box{
        width:90%;
        color:rgb(0, 119, 255);
        position:absolute;
        top:50%;
        left:50%;
        transform:translate(-50%,-50%);
        text-align:center;
    }
    
    
    
    
    .text-box h1{
        font-size:62px;
    
    }
    
    
    
    
    .text-box p{
    margin:10px 0 40px;
    font-size:14px;
    color:rgb(58, 51, 160);
    
    }
    
    
    
    
    .hero-btn{
        display:inline-block;
        text-decoration:none;
        color:rgba(4, 0, 255, 0.637);
    border:1px solid rgb(255, 255, 255);
    padding:12px 34px;
    font-size:13px;
    background:transparent;
    position:relative;
    cursor: pointer;
    font-family:Arial, Helvetica, sans-serif;
    }
    
    
    
    
    .hero-btn:hover{
        border:1px solid #f44336;
        background:#f44336;
        transition:1s;
    
    
    }
    nav .fa{
        display:none;
    }
    
    
    @media (max-width: 771px){
        .text-box h1{
            font-size:20px;
        }
        .nav-links ul lu{
            display:block;
        }
        .nav-links{
            position:absolute;
            background: #f44336;
            height:100vh;
            width:200px;
            top:0;
            right:-200px;
            text-align:left;
            z-index:2;
            transition:1s;
        }
        nav .fa{
            display:block;
            color:#fff;
            margin:10px;
            font-size:22px;
            cursor:pointer;
    
        }
        .nav-links ul{
            padding:30px;
        }
        
    }
    .course{
        width:80%;
        margin:auto;
        text-align: center;
        padding-top:100px;
    }
    h1{
        font-size:36px;
        font-weight:600;
    }
    p{
        color:#777;
        font-size: 14px;
        font-weight:300;
        line-height:22px;
        padding:10px;
    }
    
    .row{
        margin-top:5%;
        display:flex;
        justify-content:space-between;
    
    }
    .course-col{
        flex-basis:31%;
        background:#fff3f3;
        border-radius:10px;
        margin-bottom:5%;
        padding:20px 12px;
        box-sizing:border-box;
    transition:0.5s;
    
    }
    h3{
        text-align:center;
        font-weight:600;
        margin:10px 0;
    
    }
    .course-col:hover{
        box-shadow:0 0 20px 0px rgb(161, 2, 2);
    
    }
    
    @media(max-width:900px){
        .row{
            flex-direction:column;
        }
    }
    
    
    /*----campus----*/
    .campus{
        width:80%;
        margin:auto;
        text-align:center;
        padding-top:50px;
    
    }
    .campus-col{
        flex-basis:32%;
        border-radius:3px;
        margin-bottom:30px;
        position:relative;
        overflow:hidden;
    }
    .campus-col img{
        Width:100%;
        
    }
    .layer{
        background:transparent;
        height:100%;
        width:100%;
        position:absolute;
        top:0;
        left:0;
    transition:0.5s;
    }
    .layer:hover{
        background:#F44336;
    
    }
    
    .layer h3{
        width:100px;
        font-weight:500;
        color:#fff;
        font-size:26px;
        bottom:0;
        left:50%;
        transform:translatex(-50%);
        position:absolute;
        transition:0.5s;
    }
    
    .layer :hover h3{
        bottom:49%;
        opacity:1;
    
    }
    \*--------facilities--------*/
    .facilities{
        width:90%;
        margin:auto;
        text-align:center;
        padding-top:10px;
    }
    .facilities-col{
        flex-basis:31%;
        border-radius:10px;
        margin:auto;
        text-align:left;
    }
    .facilities-col img{
        width:100%;
        border-radius:10px;
    }
    .facilities-col p{
        padding:0;
    }
    .facilities-col h3{
        margin-top:16px;
        margin-bottom:15px;
        text-align:left;
    }
    /*---------testimonials-------*/
    .testimonials{
        width:80%;
        margin:auto;
        padding-top:100px;
        text-align:center;
    }
    .testimonials-col{
        flex-basis:44%;
        border-radius:10px;
        margin-bottom:5%;
        text-align:left;
        background:#fff3f3;
        padding:25px;
        cursor:pointer;
        display:flex;
    }
    .testimonials-col img{
        height:40px;
        margin-left:40px;
        margin-right:30px;
        border-radius:50%;
    
    }
    .testimonials-col p{
        padding:0;
    }
    .testimonials-col h3{
        margin-top:15px;
        text-align:left;
    }
    @media(max-width:900px){
        .testimonials-col img{
            margin-left:0px;
            margin-right:15px;
    
        }
    }
    /*--------call to action--------------*/
    .cta{
    margin:100px auto;
    width:80%;
    background-image:linear-gradient(rgba(255, 0, 0, 0.7),rgba(255, 0, 0, 0.7)),url ();
    background-position:center;
    background-size:cover;
    border-radius:10px;
    text-align:center;
    padding:100px 0;
    }
    .cta h1{
        color:#fff;
        margin-bottom:40px;
        padding:0;
    }
    @media(max-width:900px){
        .cta h1{
            font-size:24px;
        }
    }
    /*---------------footer--------------*/
    .footer{width:100%;
    text-align:center;
    padding:30px 0;
    }
    .footer h4{
        margin-bottom:auto;
        margin-top:auto;
        padding:600;
    }
    .icons .fa{
        color:#ff0000;
        margin:0 13px;
        cursor:pointer;
        padding:18px 0px;
    }
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    







        <!------Javascript for Toggle menu------>
<script>

var navLinks = document.getElementById("navLinks");
function  showMenu(){
    navLinks.style.right = "0";
}
function  hideMenu(){
    navLinks.style.right = "-200px";
}

</script>
<!--------course---------->
<section class="course">
    <h1>
       Types of Pollution
    </h1>
    <p>
       Types of Pollution
    </p>
    <div class="row">
        <div class="course-col">
        <h3>
           Air
        </h3>    
        <p>
            Air pollution is contamination of the indoor or outdoor environment by any chemical, physical or biological agent that modifies the natural characteristics of the atmosphere.
        </p>
        </div>
        <div class="course-col">
            <h3>
              Water
            </h3>    
            <p>
                Water pollution (or aquatic pollution) is the contamination of water bodies, usually as a result of human activities, so that it negatively affects its uses.
            </p>
            </div>
            <div class="course-col">
                <h3>
                    Land
                </h3>    
                <p>
                    Land pollution refers to the deterioration of the earth’s land surfaces, at and below ground level. The cause is the accumulation of solid and liquid waste materials that contaminate groundwater and soil.
                </p>
                </div>
    </div>

</section>
<!---------campus-------->
<section class="campus">
    <h1>
        Types OF Pollution
    </h1>
    <p>
        There are mainly three types of pollution Air,Water,Land.
    </p>
    <div class="row">
        <div class="campus-col">
            <img src="https://static.scientificamerican.com/blogs/cache/file/9C0D6895-2556-4662-B3C5DA872E24CF8E.jpg">
            <div class="layer">
                <h3>
                    Air Pollution
                </h3>
            </div>
        </div>
    
    <div class="row">
        <div class="campus-col">
            <img src="https://assets.nrdc.org/sites/default/files/styles/full_content--retina/public/media-uploads/guide_waterpollution_66615937_2400.jpg?itok=l7kar9Ev">
            <div class="layer">
                <h3>
                    Water Pollution
                </h3>
            </div>
        
    </div><a href="hhtps://www.lotuspetalfoundation.org/" target="_blank"></a> <div class="row">
        <div class="campus-col">
            <img src="images/1460706269.jpg">
            <div class="layer">
                <h3>
                    Land Pollution
                </h3>
            </div>
        </div>
    </div>
            </section>
<!-------Facilities-->
<section class="facilities">
    <h1>
        our facilities
    </h1>    
    <p>shfhsjfgsjdhhsdgfjashfsjfsjhfasgf</p>
<div class="row">
    <div class="facilities">
        <img src="images/images-8.jpeg">
        <p>uuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuuu</p>
        <h3>uuuuuuuu</h3>
        <i class="fa fa-star"></i>
    </div>
    
</div>


</section>
    <!---------testimonials----------->
<section class="testimonials">
    <h1> people who are saving the Earth</h1>
    <p>22 April 2016
        , 
        by Rudi Bressa
        Actors, scientists, politicians, activists. All driven by a single purpose: the protection of our Planet and environment. Because we’ve just one Earth.
        
        OCEANS
        There have been many personalities throughout history who have changed the course of events. And on the occasion of Earth Day we’ve made a list of some people who are currently committing in protecting Planet Earth.</p>
    <div class="testimonials-col">
        <img src="images/12.jpeg">
        <div>
            
            <h3>Joahn Rockstrom</h3>
            <P>He’s scientist and director of the Stockholm Resilience Centre. He’s universally recognised as one of the most qualified sustainability experts. He works as an advisor for many governments globally and, along with his research team, has developed scientific models that allow mankind to benefit from an ever-unstable planet, which is threatened by climate change and resource scarcity. In his latest book “Big World, Small Planet”, he demonstrates how the Anthropocene is the epoch when the Earth’s stability has been altered forever and how to continue to live following a pattern of sustainable development. “We take it for granted, the world that we love—and we’re destroying it so quickly. The light of dawn on the prairie. The silvery flash of fish in a stream. The cry of a hawk over a forest. Everybody has their own idea of the beautiful, and we’ll surely miss it when it’s gone”.</P>
        </div>
        <img src="images/save .jpeg">
        <div>
            <h3>Jane Goodall</h3>
            <p>Scientist, ethologist and anthropologist, she devoted her life to the study and protection of primates. She’s recently turned 82 but still travel the world to divulge her immense love for nature. She’s vegetarian and strongly supports organic farming; she never misses the opportunity to promote coexistence, simplicity and pacifism towards nature and human beings. She participated in last year’s COP21 as an ambassador and presented a documentary on the protection of forests. “You cannot get through a single day without having an impact on the world around you. What you do makes a difference, and you have to decide what kind of difference you want to make”.</p>
           
        </div>    <img src="images/earth.jpeg">
        <div>
            <h3>Bill McKibben</h3>
            <p>American environmentalist, he’s one of the founders of 350.org, the first movement that since the late ‘90s stands up against climate change and promotes the reduction of emissions. Not by chance the safe level of CO2 in the atmosphere to avoid the effects of global warming are 350 parts per million. Today we’re at over 400 ppm. He writes for UK newspaper The Guardian and is author of various books including Eaarth: Making a Life on a Tough New Planet. “A green economy is the only economy we can sustain, because if we don’t respect planetary boundaries to bring the economy forward, there simply won’t be an economy in the future”.</p>
            
        </div>
    </div>
</section>
<!-----------call to action-->
<section class="cta">
    <h1></h1>
    <a href="mailto:godrajgamer83@gmail.com" class="hero-btn"><strong><b>Suggestion</b></strong></a>
</section>
<!--------footer-------->
<section class="footer">
<h4>ABOUT US</h4>
<p>thb hrtjgrejfjhgfjhbeferfjefghrduer6ewhrurgyretb4rnvyevruiytudfterthyuretewrewthre</p>
<div class="icons">
    <a href="https://www.facebook.com/">  <i class="fa fa-facebook"></i></a>
       <a href="https://twitter.com/i/flow/login">  <i class="fa fa-twitter"></i></a>
    <a href="https://www.instagram.com/?__coig_restricted=1">  <i class="fa fa-instagram"></i>
</a>
</div>
</section>
</body>
</html>
