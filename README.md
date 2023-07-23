# netflix-clone-project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/4f0abd89da.js" crossorigin="anonymous"></script>
</head>

<body>

    <div class="header">
        <nav>
            <!-- <img src="netflixlogo.png" class="logo"> -->
            <div>
                <button class="language-btn">English <img src="images/down-icon.png" alt=""></button>
                <button>Sign In</button>
            </div>
        </nav>
        <div class="header-content">
            <h1>Unlimited movies, TV shows and more</h1>
            <h3>Watch anywhere. Cancel anytime.</h3>
            <p>Ready to watch? Enter your email to create or restart your membership.</p>
            <form class="email-signup">
                <input type="email" placeholder="Email address" required>
                <button type="submit">Get Started<i class="fa-solid fa-arrow-right"
                        style="color: #ededed;"></i></button>
            </form>
        </div>
    </div>
    <div class="divider"></div>
    <div class="features">
        <div class="row">
            <div class="text-col">
                <h1>Enjoy on your TV</h1>
                <p>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</p>
            </div>
            <div class="img-col">
                <img src="images/feature-1.png" alt="">
            </div>
        </div>
    </div>
    <div class="divider"></div>

    <div class="features">
        <div class="row">
            <div class="img-col">
                <img src="images/feature-2.png" alt="">
            </div>
            <div class="text-col">
                <h1>Download your shows to watch offline</h1>
                <p>Save your favourites easily and always have something to watch.</p>
            </div>
        </div>
    </div>
    <div class="divider"></div>

    <div class="features">
        <div class="row">
            <div class="text-col">
                <h1>Watch everywhere</h1>
                <p>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
            </div>
            <div class="img-col">
                <img src="images/feature-3.png" alt="">
            </div>
        </div>
    </div>
    <div class="divider"></div>

    <div class="features">
        <div class="row">
            <div class="img-col">
                <img src="images/asset 0.png" alt="">
            </div>
            <div class="text-col">
                <h1>Create profiles for kids</h1>
                <p>Send children on adventures with their favourite characters in a space made just for them—free with
                    your membership.</p>
            </div>
        </div>
    </div>
    <div class="divider"></div>

    <!-- FAQ -->

    <div class="FAQ">
        <h2>Frequently Asked Questions</h2>
        <div class="question">
            <p>What is Netflix?</p><i class="fa-solid fa-plus" style="color: #edeff3;"></i>
        </div>
        <div class="question">
            <p>How much does Netflix cost?</p><i class="fa-solid fa-plus" style="color: #edeff3;"></i>
        </div>
        <div class="question">
            <p>Wher can I watch?</p><i class="fa-solid fa-plus" style="color: #edeff3;"></i>
        </div>
        <div class="question">
            <p>How do I cancel?</p><i class="fa-solid fa-plus" style="color: #edeff3;"></i>
        </div>
        <div class="question">
            <p>What can I watch on Netflix?</p><i class="fa-solid fa-plus" style="color: #edeff3;"></i>
        </div>
        <div class="question">
            <p>Is Netflix good for kids?</p><i class="fa-solid fa-plus" style="color: #edeff3;"></i>
        </div>
        

        <div class="FAQ-sign-up">
            <p>Ready to watch? Enter your email to create or restart your membership.</p>
            <form class="email-signup">
                <input type="email" placeholder="Email address" required>
                <button type="submit">Get Started<i class="fa-solid fa-arrow-right"
                        style="color: #ededed;"></i></button>
            </form>
        </div>
    </div>

    <div class="divider"></div>


</body>

</html>




css 

*{
    box-sizing:border-box;
    padding:0;
    margin:0;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#000;
    color:#ffff;
}

.header{
    width:100%;
    height:90vh;
    background-image: linear-gradient(to top,rgba(0, 0, 0, 0.8)0,rgba(0, 0, 0, 0) 60% ,rgba(0, 0, 0, 0.8)100%),url(images/header-image.jpg);
    background-size: cover;
    background-position: center;
    padding:10px 12%;
    position:relative;

}

nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding:10px 0;
}

.logo{
    width: 150px;
    cursor: pointer;
}

nav button{
    font-size: 14px;
    border:solid 1px #db0001;
    padding:7px 15px;
    color:white;
    background-color: #db0001 ;
    border-radius: 4px;
    margin-left: 10px;
    cursor:pointer;
}

.language-btn{
    display:inline-flex;
    align-items: center;
    background:transparent;
    border:solid 1px #fff;
    padding:7px 15px;
}

.language-btn img{
    width:10px;
    margin-left: 10px;
}

.header-content{
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    text-align:center;
    margin-top: 50px;
}

.header-content h1{
    font-size: 52px;
    line-height: 60px;
    font-weight: 1000;
    max-width: 650px;
}

.header-content h3{
    font-weight:14;
    font-size:1.5rem;
    margin-top: 13px;
    margin-bottom: 20px;
}

.header-content p{
    font-size:1.1rem;
    margin-bottom: 15px
}

.email-signup input{
    flex:1;
    border:solid 1px #fff;
    border-radius: 5px;
    font-size: 1.1rem;
    padding:15px 30px;
    padding-right:100px;
    background: transparent;
    color:#000;
    
}

.email-signup button{
    flex:1;
    font-size: 1.2rem;
    color:#fff;
    background: #db0001;
    border:solid 1px #db0001;
    padding:15px 30px;
    border-radius:5px;
    margin-left: 10px;
    cursor:pointer;
}

.email-signup button i{
     margin-left:10px;
}

/* ---------------------divider------------------ */

.divider{
    height:7px;
    background-color: #393636;
}

/* ----------------features-------------- */

.features{
    padding:50px 12%;
    font-size:22px;
}

.row{
    display: flex;
    width:100%;
    align-items: center;
    flex-wrap:wrap;
    margin-top:50px;
    justify-content: space-between;
}

.text-col{
    flex-basis:47%;
    margin-bottom:20px;
}

.img-col{
    flex-basis:50%;
    margin-bottom:20px;
}

.img-col img{
    display:block;
    width:100%;
    margin:auto;
}

.text-col h1{
    font-size: 50px;
    font-weight:900;
    margin-bottom:20px;
}

/* --------------FAQ-------------------- */

.FAQ{
    /* height:110vh; */
    padding:50px 12%;
}

.FAQ h2{
    font-size:50px;
    text-align: center;
    margin-bottom:30px;
    font-weight: 900;
}

.question{
    display: flex;
    justify-content: space-between;
    background-color:#393636;
    padding:25px 20px;
    margin-bottom:15px;
}

.question p{
    font-size:26px;
}

.question i{
    font-size:30px;    
}

.FAQ-sign-up{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-block:20px;
}

.FAQ-sign-up p{
    margin-bottom: 15px;
}





























