# hello-hi
My first reciprocity on github

:root{
    --yellow:#e51919db;
}

*{
    font-family: 'Nunito', sans-serif;
    margin:0; padding:0;
    box-sizing: border-box;
    text-decoration: none;
    outline: none; border:none;
    text-transform: capitalize;
    transition: all .2s linear;
}

*::selection{
    background:var(--yellow);
    color:rgb(66, 63, 63);
}

html{
    font-size: 62.5%;
    overflow-x: hidden;
}

html::-webkit-scrollbar{
    width:1.4rem;
}

html::-webkit-scrollbar-track{
    background:#222;
}

html::-webkit-scrollbar-thumb{
    background:var(--yellow);
}

body{
    background:#111;
    overflow-x: hidden;
    padding-left: 35rem;
}

section{
    min-height: 100vh;
    padding:1rem;
}

.btn{
    padding:.7rem 3rem;
    background:#333;
    color:#fff;
    cursor: pointer;
    margin-top: 1rem;
    font-size: 2rem;
    border-radius: 5rem;
}

.btn i{
    padding:0 .5rem;
    font-size: 1.8rem;
}

.btn:hover{
    background:var(--yellow);
}

.heading{
    text-align: center;
    margin:0 6rem;
    font-size: 4rem;
    padding:1rem;
    border-bottom: .1rem solid #fff4;
    color:#fff;
}

.heading span{
    color:var(--yellow);
}

header{
    position: fixed;
    top:0; left:0;
    z-index: 1000;
    height:100%;
    width:35rem;
    background:#1a1a1a;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
    text-align: center;
}

header .user img{
    height:17rem;
    width:17rem;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 1rem;
    border:.7rem solid var(--yellow);
}

header .user .name{
    font-size: 3.5rem;
    color:#fff;
}

header .user .post{
    font-size: 2rem;
    color:#eee;
}

header .navbar{
    width:100%;
}

header .navbar ul{
    list-style: none;
    padding:1rem 3rem;
}

header .navbar ul li a{
    display: block;
    padding:1rem;
    margin:1.5rem 0;
    background:#333;
    color:#fff;
    font-size: 2rem;
    border-radius: 5rem;
}

header .navbar ul li a:hover{
    background:var(--yellow);
}

#menu{
    position: fixed;
    top:2rem; right:2rem;
    background:#333;
    color:#fff;
    cursor: pointer;
    font-size: 2.5rem;
    padding:1rem 1.5rem;
    z-index: 1000;
    display: none;
}

.home{
    display: flex;
    justify-content: center;
    flex-flow: column;
    padding:0 15rem;
}

.home h3{
    font-size: 2.5rem;
    color:#fff;
}

.home h1{
    font-size:5rem;
    color:#fff;
}

.home h1 span{
    color:var(--yellow);
}

.home p{
    font-size:2rem;
    color:#eee;
    padding: 1rem 0;
}

.about .row{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    padding:1rem 0;
}

.about .row .info{
    flex:1 1 48rem;
    padding:2rem 1rem;
    padding-left: 6rem;
}

.about .row .info h3{
    font-size: 2rem;
    color:var(--yellow);
    padding:1rem 0;
    font-weight: normal;
}

.about .row .info h3 span{
    color:#eee;
    padding:0 .5rem;
}

.about .row .counter{
    flex:1 1 48rem;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.about .row .counter .box{
    width:20rem;
    background:#222;
    text-align: center;
    padding: 2rem;
    margin:2rem;
}

.about .row .counter .box span{
    font-size: 4rem;
    color:var(--yellow);
}

.about .row .counter .box h3{
    font-size: 2rem;
    color:#fff;
}

.education .box-container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    padding:1rem 0;
    padding-left: 3rem;
}

.education .box-container .box{
    width:27rem;
    margin:4rem 1rem;
    padding-left: 4rem;
    border-left: .2rem solid #fff;
    position: relative;
}

.education .box-container .box span{
    font-size: 1.3rem;
    background:#222;
    color:#fff;
    border-radius: 5rem;
    padding:.5rem 2.5rem;
}

.education .box-container .box h3{
    font-size: 2rem;
    color:#fff;
    padding-top: 1.5rem;
}

.education .box-container .box p{
    font-size: 1.4rem;
    color:#eee;
    padding: 1rem 0;
}

.education .box-container .box i{
    position: absolute;
    top:-1.5rem; left:-2.5rem;
    height:5rem;
    width: 5rem;
    border-radius: 50%;
    line-height: 5rem;
    text-align: center;
    font-size: 2rem;
    color:#fff;
    background:var(--yellow);
}

.contact .row{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
}

.contact .row .content{
    flex:1 1 30rem;
    padding:4rem;
    padding-bottom: 0;
}

.contact .row form{
    flex:1 1 45rem;
    padding:2rem;
    margin:2rem;
    margin-bottom: 4rem;
}

.contact .row form .box{
    padding:1.5rem;
    margin:1rem 0;
    background:#3333;
    color:#fff;
    text-transform: none;
    font-size: 1.7rem;
    width:100%;
}

.contact .row form .box::placeholder{
    text-transform: capitalize;
}

.contact .row form .message{
    height: 15rem;
    resize: none;
}

.contact .row .content .title{
    text-transform: uppercase;
    color:#fff;
    font-size: 3rem;
    padding-bottom: 2rem;
}

.contact .row .content .info h3{
    display: flex;
    align-items: center;
    font-size: 2rem;
    color:#eee;
    padding:1rem 0;
    font-weight: normal;
}

.contact .row .content .info h3 i{
    padding-right: 1rem;
    color:var(--yellow);
}

.top{
    position: fixed;
    bottom:7.5rem; right: 2rem;
    z-index: 100;
    display: none;
}

















/* media queries  */

@media (max-width:1200px){

    html{
        font-size: 55%;
    }

    .home{
        padding:1rem 4rem;
    }

}

@media (max-width:991px){

   header{
       left:-120%;
   }

   #menu{
       display: block;
   }

   header.toggle{
    left:0%;
   }

   body{
       padding:0;
   }

}

@media (max-width:768px){

    html{
        font-size: 50%;
    }
 
 }

@media (max-width:400px){

    header{
        width: 100vw;
    }

    .heading{
        margin:0 3rem;
    }

    .about .row .counter .box{
        width: 100%;
    }
 
    .education .box-container .box{
        width:100%;
    }

    .portfolio .box-container .box{
        width:100%;
    }

    .contact .row form{
        margin:3rem 0;
    }

 }
 
 
 
 
 <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>responsive personal portfolio website design tutorail</title>

    <!-- font awesome cdn link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css">

    <!-- custom css file link  -->
    <link rel="stylesheet" href="styles.css">

</head>
<body>
    
<!-- header section starts  -->

<header>
    
        
    
    <div class="user">
        <h3 class="name">DILIP C</h3>
        <p class="post">Engineering student</p>
    </div>

    <nav class="navbar">
        <ul>
            <li><a href="#home">home</a></li>
            <li><a href="#about">about</a></li>
            <li><a href="#education">education</a></li>
            <li><a href="#contact">contact</a></li>
        </ul>
    </nav>

</header>

<!-- header section ends -->

<div id="menu" class="fas fa-bars"></div>

<!-- home section starts  -->

<section class="home" id="home">

    <h3>HI THERE !</h3>
    <h1>I'M <span>DILIP C</span></h1>
    </p>
    <a href="#about"><button class="btn">about me <i class="fas fa-user"></i></button></a>

</section>

<!-- home section ends -->

<!-- about section starts  -->

<section class="about" id="about">

<h1 class="heading"> <span>about</span> me </h1>

<div class="row">

    <div class="info">
        <h3> <span> name : </span> DILIP C </h3>
        <h3> <span> age : </span> 20 </h3>
        <h3> <span> qualification : </span> BE </h3>
        <h3> <span> language : </span> English, Kannada</h3>
        <a href="#"><button class="btn"> download CV <i class="fas fa-download"></i> </button></a>
    </div>

    <div class="counter">

        <div class="box">
            <span>84%</span>
            <h3>In BE</h3>
        </div>

        <div class="box">
            <span>90%</span>
            <h3>In class 12 </h3>
        </div>

        <div class="box">
            <span>88%</span>
            <h3>In class 10</h3>
        </div>

        <div class="box">
            <span>great</span>
            <h3>Learner</h3>
        </div>

    </div>

</div>

</section>

<!-- about section ends -->

<!-- education section starts  -->

<section class="education" id="education">

<h1 class="heading"> my <span>education</span> </h1>

<div class="box-container">

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2017-18</span>
        <h3>class 10</h3>
        <p> BGS United School</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2020-20</span>
        <h3>class 12</h3>
        <p>Sri Chaitanya PU College</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2020-24</span>
        <h3>BE</h3>
        <p>Sai Vidya Institute Of Technology</p>
    </div>

</div>

</section>

<!-- education section ends -->

<!-- contact section starts  -->

<section class="contact" id="contact">

<h1 class="heading"> <span>contact</span> me </h1>

<div class="row">

    <div class="content">

        <h3 class="title">contact info</h3>

        <div class="info">
            <h3> <i class="fas fa-envelope"></i> dilipcofficial@gmail.com</h3>
            <h3> <i class="fas fa-phone"></i> +91 9900455915</h3>
            <h3> <i class="fas fa-phone"></i> +91 6360054692 </h3>
            <h3> <i class="fas fa-map-marker-alt"></i> Bengaluru,Karnataka,560090  </h3>
        </div>

    </div>

    <form action="">

        <input type="text" placeholder="name" class="box">
        <input type="email" placeholder="email" class="box">
        <input type="text" placeholder="project" class="box">
        <textarea name="" id="" cols="30" rows="10" class="box message" placeholder="message"></textarea>
        <button type="submit" class="btn"> send <i class="fas fa-paper-plane"></i> </button>

    </form>

</div>

</section>

<!-- contact section ends -->

<!-- scroll top button  -->

<a href="#home" class="top">
    <img src="images/scroll-top-img.png" alt="">
</a>

</body>
</html>





$(document).ready(function(){

  $('#menu').click(function(){
    $(this).toggleClass('fa-times');
    $('header').toggleClass('toggle');
  });

  $(window).on('scroll load',function(){
    
    $('#menu').removeClass('fa-times');
    $('header').removeClass('toggle');

    if($(window).scrollTop() > 0){
      $('.top').show();
    }else{
      $('.top').hide();
    }

  });

  // smooth scrolling 

  $('a[href*="#"]').on('click',function(e){

    e.preventDefault();

    $('html, body').animate({

      scrollTop : $($(this).attr('href')).offset().top,

    },
      500, 
      'linear'
    );

  });

});




