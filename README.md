<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trafalgar</title>
    
    <link href="style.css" rel="stylesheet">
    <link href="Icons/css/all.min.css" rel="stylesheet">
</head>
<body>
    <style>
        /* General  */
* {
    margin: 0;
    padding: 0;
    font-weight: normal;
}
@font-face {
    font-family: Mulish-Regular;
    src: url(../Fonts/Mulish-Regular.ttf);
}
@font-face {
    font-family: Mulish-SemiBold;
    src: url(../Fonts/Mulish-SemiBold.ttf);
}
@font-face {
    font-family: Mulish-Light;
    src: url(../Fonts/Mulish-Light.ttf);
}
@font-face {
    font-family: Mulish-Bold;
    src: url(../Fonts/Mulish-Bold.ttf);
}
html {
    font-size: 16px;
    font-family: Mulish-Light;
    color: rgba(31, 21, 52, 1);
}
img {
    max-width: 100%;
    height: auto;
}

/* Header  */
.container {
    width: 80%;
    margin-inline: auto;
}
    /* navbar */
.navbar {
    display: flex;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: space-between;
    padding-block: 56px;
}
.navbar ul{
    position: relative;
    left: -5%;
}
.navbar-link {
    display: inline;
    margin-inline-end: 2.25rem;
    
}
.navbar-link a{
    text-decoration: none;
    opacity: 50%;
    font-family: Mulish-Regular;
    color: rgba(31, 21, 52, 1);
}
.navbar-link:first-child a{
    font-family: Mulish-Bold;
    opacity: 100%;
}
.navbar-link a:hover {
    opacity: 100%;
}
.navbar-link:last-child {
    margin-inline-end: 0;
}
    /* hero */
.hero {
    display:flex;
    align-items: center;
    justify-content: space-between;
}

.hero .text h2{
    font-size: 3rem;
    font-family: Mulish-Bold;
    max-width: 415px;
    margin-bottom: 1.5rem;
}
.hero .text p{
    font-size: 1.31rem;
    color: rgba(125, 121, 135, 1);
    max-width: 75%;
    line-height: 2rem;
    margin-bottom: 2.5rem;
}
header {
    background-image: url(../Images/element.png);
    background-repeat: no-repeat;
    background-position: left top 160px;
    margin-bottom: 10rem;
}
.button {
    text-decoration: none;
    color:rgba(255, 255, 255, 1);
    font-size: 0.9rem;
    font-family: Mulish-Bold;
    background-color: rgba(69, 143, 246, 1);
    display: inline-block;
    padding-block: 16px;
    text-align: center;
    border-radius: 55px;
    width: 200px;
}
.our-services {
    padding-block: 64px;
    background-image: url(../Images/Vector.png),url(../Images/element2.png);
    background-repeat: no-repeat;
    background-position: left -20px top 260px,right 11% top 53%;
    margin-bottom: 10rem;
}
.our-services .text{
    width: 60%;
    margin-inline: auto;
    margin-bottom: 56px;
}
.our-services .text h3 {
    font-size: 2.25rem;
    font-family: Mulish-Bold;
    text-align: center;
    position: relative;
    margin-bottom: 64px;
}
.our-services .text h3::after{
    content: '';
    display: block;
    border-style: hidden;
    margin-top: 32px;
    background-color: black;
    width: 3.5rem;
    height: 0.125rem;
    border-radius: 5px;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
}
.our-services .text  p{
    font-size: 1.125rem;
    color: rgba(125, 121, 135, 1);
    text-align: center;
    line-height: 1.875rem;
}
.our-services .cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    width: 75%;
    margin-inline: auto;
    margin-bottom: 56px;
}
.our-services .cards .card {
    background-color:  rgba(255, 255, 255, 1);
    padding-inline: 1.625rem;
    box-shadow: 10px 40px 50px 0px rgba(229, 233, 246, 0.4);
    padding-block: 64px;
    height: auto;
    margin: 15px;
    border-radius: 1.25rem;
    width: calc( (100% / 3 ) -  2 * 15px - 2 * 26px);
}
.our-services .cards .card img{
    width: auto;
    max-height: 71px;
    margin-bottom: 20px;
}
.our-services .cards .card h4 {
    font-size: 1.5rem;
    font-family: Mulish-Bold;
    margin-bottom: 20px;
}
.our-services .cards .card p{
    color: rgba(125, 121, 135, 1);
    line-height: 1.75rem;
    max-width: 82%;
}
.primary-button{
    background-color: white;
    color:rgba(69, 143, 246, 1);
    border: solid 1.4px;
}
.primary-button:hover {
    background-color: rgba(69, 143, 246, 1);
    color: white;
}
.our-services .primary-button {
    display: block;
    margin-inline: auto;
}
.healthcare-prov {
    width: 85%;
    margin-inline: auto;
    display: flex;
    flex-wrap:nowrap;
    justify-content: space-between;
    align-items: center;
    position:relative;
}

.healthcare-prov .text{
    width: 30%;
    margin-inline: auto;
    position: relative;
    top: 12px;
    
}
.healthcare-prov .text h2{
    font-size: 2.25rem;
    font-family: Mulish-Bold;
    line-height: 3.5rem;
    position: relative;
    margin-bottom: 64px;
}
.healthcare-prov .text h2::after {
    content: '';
    display: block;
    border-style: hidden;
    margin-top: 32px;
    background-color: black;
    width: 3.5rem;
    height: 0.125rem;
    border-radius: 5px;
    position: absolute;
}
.healthcare-prov .text p {
    font-size: 1.125rem;
    line-height: 1.875rem;
    color: rgba(125, 121, 135, 1);
    margin-bottom: 38px;
}
.download-our-apps {
    width: 83%;
    margin-inline-start: auto;
    flex-wrap: nowrap;
    justify-content: space-between;
    display: flex;
    align-items: center;
    background-image: url(../Images/element.png);
    background-repeat: no-repeat;
    background-position: top right 1%;
    padding-block: 20rem;
}
.download-our-apps .text {
    width: 30%;
}
.download-our-apps img{
    margin-inline-end: 10%;
}
.download-our-apps .text h2 {
    font-size: 2.25rem;
    font-family: Mulish-Bold;
    line-height: 3rem;
    max-width: 300px;
    position: relative;
    margin-bottom: 64px;
}
.download-our-apps .text h2::after {
    content: '';
    display: block;
    border-style: hidden;
    margin-top: 32px;
    background-color: black;
    width: 3.5rem;
    height: 0.125rem;
    border-radius: 5px;
    position: absolute;
}
.download-our-apps .text p {
    font-size: 1.125rem;
    line-height: 1.875rem;
    color: rgba(125, 121, 135, 1);
    margin-bottom: 38px;
}
.download-our-apps .text .primary-button i{
    margin-inline-start: 0.5625rem;
}
.whole-testimonials{
    width: 70%;
    position: relative;
    padding-inline: 4%;
    left: 50%;
    transform: translateX(-50%);
    background-image: url(../Images/element.png);
    background-repeat: no-repeat;
    background-position: left bottom 46px;
    margin-bottom: 20rem;
}

.blue-testimonials {
    background-image: linear-gradient(208.18deg, #67C3F3 9.05%, #5A98F2 76.74%);
    background-repeat: no-repeat;
    padding-block: 64px 91px;
    padding-inline: 128px;
    border-radius: 24px;
    position: relative;
    margin-bottom: 36px;
}
.blue-testimonials::after {
    content: url(../Images/Group.png);
    position: absolute;    
    right: -45px;
    top: -15px;
}
.blue-testimonials h2{
    font-size: 2.25rem;
    font-family: Mulish-Bold;
    color: white;
    text-align: center;
    position: relative;
    margin-bottom: 86px;
}
.blue-testimonials h2::after{
    content: '';
    display: block;
    border-style: hidden;
    margin-top: 28px;
    background-color: white;
    width: 3.5rem;
    height: 0.125rem;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 5px;
    position: absolute;
}
.blue-testimonials .founder {
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
    align-items: center;
    width: 98%;
    margin-inline: auto;
}
.blue-testimonials .founder p{
    font-size: 1.1875rem;
    line-height: 1.875rem;
    color: rgba(255, 255, 255, 0.9);
    font-family: Mulish-Regular;
    max-width: 405px;
}
.blue-testimonials .founder img{
    border-radius: 50% 50%;
    border: solid white 4px;
}
.blue-testimonials .founder .founder-text {
    margin-inline-end: 85px;
}
.blue-testimonials .founder .founder-text h5{
    font-size: 1.375rem;
    font-family: Mulish-Bold;
    color: rgba(255, 255, 255, 1);
    margin-bottom: 5px;
}
.blue-testimonials .founder .founder-text h6{
    font-size: 1.125rem;
    font-family: Mulish-Regular;
    color: rgba(255, 255, 255, 0.85);
}
.whole-testimonials .slider {
    width: 60%;
    margin-inline: auto;
    position: relative;
    min-width: 650px;
}
.whole-testimonials .slider .elements {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
}
.whole-testimonials .slider .elements a:first-child{
    margin-inline-end: 92px;
    color: rgba(69, 143, 246, 1);
    opacity: 50%;
}
.whole-testimonials .slider .elements a:last-child {
    margin-inline-start: 92px;
    color: rgba(69, 143, 246, 1);
    opacity: 100%;
}
.whole-testimonials .slider .elements img{
    margin-inline: 6px;
}


.article{
    background-image: url(../Images/element2.png),url(../Images/element2.png) ;
    background-repeat: no-repeat,no-repeat;
    background-position: top 15.5% left 13%, bottom -45px right 91.42px;
    position: relative;
    padding-bottom: 10rem;
}
.article h3 {
    font-size: 2.25rem;
    font-family: Mulish-Bold;
    text-align: center;
    position: relative;
    margin-bottom: 8rem;
}
.article::before{
    content: '';
    position: absolute;
    width:100%;
    height: 100%;
    background-image: url(../Images/VectorNearFooter.png);
    background-position: right top 25%;
    background-repeat: no-repeat;
    opacity: 60%; 
    z-index: -1; 
}
.article h3::after {
    content:'';
    display: block;
    border-style: hidden;
    margin-top: 32px;
    background-color: black;
    width: 3.5rem;
    height: 0.125rem;
    border-radius: 5px;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
}
.article .article-cards {
    display: flex;
    flex-wrap:nowrap;
    margin-inline:auto;
    justify-content: center;
    width: 72%;
    margin-bottom: 64px;
}
.article .article-cards .a-card {
    margin-inline: 15px;
    background-color: rgba(255, 255, 255, 1);
    box-shadow: 10px 40px 50px 0px rgba(229, 233, 246, 0.4);
    border-radius: 20px;
}
.article .article-cards .a-card img{
    border-radius: 20px 20px 0 0;
}
.article .article-cards .a-card .card-text {
    padding: 20px 30px 40px;
}
.article .article-cards .a-card h4{
    font-size: 1.3125rem;
    font-family: Mulish-Bold;
    line-height: 2rem;
    max-width: 260px;
    margin-bottom: 8px;
}
.article .article-cards .a-card p {
    line-height: 1.75rem;
    color: rgba(125, 121, 135, 1);
    max-width: 261px;
    margin-bottom: 20px;
}
#link {
    text-decoration: none;
    font-family: Mulish-SemiBold;
    color: rgba(64, 137, 237, 1);
    font-size: 1.0625rem;
}
#link i{
    margin-inline-start: 10px;
}
.article a {
    display: block;
    margin-inline: auto;
}
footer {
    background-image: linear-gradient(183.41deg, #67C3F3 -8.57%, #5A98F2 82.96%);
    padding-block: 126px;
    padding-inline-start: 12%;
    padding-inline-end: 16%;
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
    align-items: flex-start;
    position: relative;
}
footer::after {
    content: url(../Images/elementfoot.svg);
    position: absolute;    
    left: 0;
    bottom: 0;
    overflow: hidden;
}
.col-two, .col-three, .col-four{
    padding-top: 3.5px
}
.coloumn h5 {
    font-size: 1.25rem;
    font-family: Mulish-Bold;
    color: white;
}
.coloumn ul{
    list-style: none;
}

.coloumn li{
    margin-block: 20px;
}

.coloumn li:first-child{
    margin-block-start: 27px;
}
.coloumn a{
    text-decoration: none;
    font-size: 1.125rem;
    color: white;
}
.logo {
    width: 160px;
    display: flex;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 15px;
}
.logo .img-bg{
    width: 41px;
    height: 41px;
    border-radius: 50%;
    background-color: white;
    display: flex;
    align-items: center;
    justify-content: center;
}
.col-one .logo h5 {
    font-size: 1.5rem;
    font-family: Mulish-Bold;
    color: white;
}
.col-one p{
    font-size: 1.125rem;
    color: white;
    line-height: 1.75rem;
    max-width: 380px;
    margin-bottom: 32px;
}
.col-one #citation{
    margin-bottom: 0;
    font-size: 1rem;
}
    </style>
    <header>
        <section class="container">
            <nav class="navbar">
            <!--Left-->
                <a href="#"><img src="Images/logo.svg"></a>
            <!--Right-->
                <ul>
                    <li class="navbar-link"><a href="#" >Home</a></li>
                    <li class="navbar-link"><a href="#" >Find a doctor</a></li>
                    <li class="navbar-link"><a href="#" >Apps</a></li>
                    <li class="navbar-link"><a href="#" >Testimonials</a></li>
                    <li class="navbar-link"><a href="#" >About us</a></li>
                </ul>
            </nav>
        </section>
        <!-- hero part -->
        <section class="container hero">
            <!-- text part -->
            <div class="text">
            <h2>Virtual healthcare for 
                you</h2>
            <p>Trafalgar provides progressive, and affordable healthcare, 
                accessible on mobile and online for everyone</p>
            <a href="#" class="button">Consult today</a>
            </div>
            <!-- text part-->
            <img src="Images/illustration.png">
        </section>
    </header>
        <!-- our services div -->
        <div class="our-services">
            <!-- text div -->
            <div class="text">
                <h3>Our services</h3>
                <p>We provide to you the best choiches for you. Adjust it to your health 
                    needs and make sure your undergo treatment with 
                    our highly qualified doctors you can consult with us which 
                    type of service is suitable for your health</p>
            </div>
            <!-- cards div -->
            <div class="cards">
                <!-- card div -->
                <div class="card">
                    <img src="Images/Frame.png">
                    <h4>Search doctor</h4>
                    <p>Choose your doctor from thousands of specialist, 
                        general, and trusted hospitals</p>
                </div>
                <!-- card div -->
                <div class="card">
                    <img src="Images/Frame2.png">
                    <h4>Online pharmacy</h4>
                    <p>Buy your medicines with our <br> mobile application 
                        with a simple delivery system</p>
                </div>
                <!-- card div -->
                <div class="card">
                    <img src="Images/Frame3.png">
                    <h4>Consultation</h4>
                    <p>Free consultation with our trusted doctors 
                        and get the best recomendations</p>
                </div>
                <!-- card div -->
                <div class="card">
                    <img src="Images/Frame4.png">
                    <h4>Details info</h4>
                    <p>Free consultation with our trusted doctors and get the 
                        best recomendations</p>
                </div>
                <!-- card div -->
                <div class="card">
                    <img src="Images/Frame5.png">
                    <h4>Emergency care</h4>
                    <p>You can get 24/7 urgent care for yourself or your 
                        children and your lovely family</p>
                </div>
                <!-- card div -->
                <div class="card">
                    <img src="Images/Frame6.png">
                    <h4>Tracking</h4>
                    <p>Track and save your medical history and health data</p>
                </div>
            </div>
            <a class="button primary-button" href="#">Learn more</a>
        </div>
        <!-- leading healthcare providers div -->
         <div class="healthcare-prov">
            <!-- text part div -->
             <img src="Images/trafalgar-illustration.png">
             <div class="text">
                <h2>Leading healthcare providers</h2>
                <p>Trafalgar provides progressive, and affordable 
                    healthcare, accessible on mobile and online for everyone. To us,
                     it’s not just work. We take pride in the solutions we deliver</p>
                <a class="button primary-button" href="#">Learn more</a>
             </div>
         </div>
        <!-- download our mobile apps div  -->
         <div class="download-our-apps">
            <div class="text">
                <h2>Download our mobile apps</h2>
                <p>Our dedicated patient engagement app and web portal
                     allow you to
                     access information instantaneously 
                    (no tedeous form, long calls, or administrative hassle) and securely</p>
                <a class="button primary-button" href="#">Download <i class="fa-solid fa-arrow-down"></i></a>
             </div>
             <img src="Images/trafalgar-illustration2.png">
            </div>
        <!-- Testimonials div -->
         <div class="whole-testimonials">
                <div class="blue-testimonials">
                     <!-- header -->
                     <h2>What our customer are saying</h2>
                    <!-- founder div -->
                        <div class="founder">
                            <img src="Images/image1.png">
                            <div class="founder-text">
                                <h5>Edward Newgate</h5>
                                <h6>Founder Circle</h6>
                            </div>
                            <p>“Our dedicated patient engagement app and web portal allow you 
                            to access information instantaneously
                             (no tedeous form, long calls, or administrative hassle)
                              and securely”</p>
                        </div>
                </div>
            <!-- slider div -->
            <div class="slider">
                <div class="elements">
                    <a href="#"><i class="fa-solid fa-arrow-left-long"></i></a>
                    <img src="Images/EllipseSliderDark.png">
                    <img src="Images/EllipseSliderLight.png">
                    <img src="Images/EllipseSliderLight.png">
                    <img src="Images/EllipseSliderLight.png">
                    <a href="#"><i class="fa-solid fa-arrow-right-long"></i></a>
                </div>
            </div>

        </div>
        <!-- our latest article div -->
        <div class="article">
            <h3>Check out our latest article</h3>
            <!-- cards div -->
            <div class="article-cards">
                <!-- card div -->
                <div class="a-card">
                    <img src="Images/image2.png">
                    <div class="card-text">
                        <h4>Disease detection, check up in the laboratory</h4>
                        <p>In this case, the role of the health laboratory
                         is very important to do<br> a disease detection...</p>
                        <a  href="#" id="link">Read more <i class="fa-solid
                             fa-arrow-right-long">
                        </i>
                        </a>
                    </div>
                </div>
                <!-- card div -->
                <div class="a-card">
                    <img src="Images/image3.png">
                    <div class="card-text">
                        <h4>Herbal medicines that are safe for consumption</h4>
                         <p>Herbal medicine is very widely used at 
                        this time because of its 
                        very good for your health...</p>
                        <a  href="#" id="link">Read more <i class="fa-solid 
                            fa-arrow-right-long"></i></a>
                    </div>
                </div>
                <!-- card div -->
                <div class="a-card">
                    <img src="Images/image4.png">
                    <div class="card-text">
                        <h4>Natural care for healthy facial skin</h4>
                        <p>A healthy lifestyle should start from now and 
                        also for your skin health. There are some...</p>
                        <a  href="#" id="link">Read more <i class="fa-solid 
                            fa-arrow-right-long"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="button primary-button">View all</a>
        </div>
     <footer>
        <div class="coloumn col-one">
            <div class="logo">
                <span class="img-bg"><img src="Images/T.svg"></span>
                <h5>Trafalgar</h5>
            </div>
            <p>Trafalgar provides progressive, and affordable healthcare,
                 accessible on mobile and online<br> for everyone</p>
            <p id="citation">©Trafalgar PTY LTD 2020. All rights reserved</p>
        </div>
        <div class="coloumn col-two">
            <h5>Company</h5>
            <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Testimonials</a></li>
                <li><a href="#">Find a doctor</a></li>
                <li><a href="#">Apps</a></li>
            </ul>
        </div>
        <div class="coloumn col-three">
            <h5>Region</h5>
            <ul>
                <li><a href="#">Indonesia</a></li>
                <li><a href="#">Singapore</a></li>
                <li><a href="#">Hongkong</a></li>
                <li><a href="#">Canada</a></li> 
             </ul>
        </div>
        <div class="coloumn col-four">
            <h5>Help</h5>
            <ul>
                <li><a href="#">Help center</a></li>
                <li><a href="#">Contact support</a></li>
                <li><a href="#">Instructions</a></li>
                <li><a href="#">How it works</a></li>
            </ul>
        </div>  
     </footer>    
</body>
</html>

