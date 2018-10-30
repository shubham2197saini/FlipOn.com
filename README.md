# FlipOn.com
This is an e-commence websites .
/*home page*/
<hmtl>
    <head>
        <title>::My Shop::</title>
        <meta charset="utf-8">
        
         <link href="https://use.fontawesome.com/releases/v5.4.2/css/all.css" rel="stylesheet" type="text/css">
        
        <link href="css/jquery.bxslider.css" rel="stylesheet" type="text/css">
        
        <link href="css/style.css" rel="stylesheet" type="text/css">
        
        <link href="css/media.css" rel="stylesheet" type="text/css">
        
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
         
        <script>
         $(document).ready(function(){
    $(".search-area").on({
        click: function(){
            $(this).css("background-color", "#f0f03a");
        } , 
       mouseleave: function(){
            $(this).css("background-color", "white");
        }
        
    });
});      
        </script>
          <script>
         $(document).ready(function(){
    $(".search-area").on({
        click: function(){
            $(this).css("background-color", "#f0f03a");
        } , 
       mouseleave: function(){
            $(this).css("background-color", "white");
        }
        
    });
});      
        </script>
        <script>
            $(document).ready(function(){

var re = /(\w+)\@(\w+)\.[a-zA-Z]/g;
var email = getElementById("input1");
var emailValue = email.value;
var testEmail = re.test(emailValue);

    $('.sub1').click(function(){
    if(!testEmail){
        alert("Please enter a valid email");
    } else {
        confirm("Is " + emailValue + " the email you want to use?");
    }
    });
});
        </script>
        
    </head>
    
<body>
    
    <div id="wrapper"> 
    <div id="header">    
    <div id="subheader">    
     
        <div class="container">
            <p> world Fastest Online Shopping websites</p>
            <a href="#">Contact Us</a> <a href="#">Downlaod App</a> <a href="#">Downlaod App</a> <a href="#">Home</a>
        </div>
        </div>
        <div id="main-header">
            
            <div id="logo">
            <span id="ist">Flip</span><span id="iist">ON.com</span>
            </div>
            
     <div id="search">
     
         <form>
    <input class="search-area" type="text" name="text" placeholder="serach here. .">
    <input class="search-btn"  type="submit" name="submit" value="SEARCH">
     </form>
      
    </div>
            <div id="user">
                <li> <a href="SignUp.html">&#9442;SignIn</a> </li> 
                <li> <a href="cart2.html">&#128722;Cart</a> </li> 
            </div>
    
        </div>
                </div>

        <!--navigation bar--->
        <!--<div id="navigation">
           <nav>
               <a href="#">Home</a>
               <a href="#">New Arrivals</a>
                <a href="#">Deals</a>
               <a href="#">Electronics</a>
               <a href="#">Accessroies</a>
              <a href="#">Products</a>
              <a href="#">My Order</a>
               
           </nav> 
        </div>-->
        <div id="navigation">
    <nav >       <!--like p,list tag-->
            
    <ul class="top" id="dropclick">
        
        
        
        <li>
            <a href="#news">&#127969;Home</a>
           
        </li>
        
              <li><a href="#news">	&#128478;New Arrivals	</a>
        </li>
           <li>   <a href="#contact">&#128241;Deals	</a> 
        </li>
        <li>
            <a href="#about">&#128241;Products</a>
             <ul class="dropdown-content">
                 <li>Men's</li>
                  <li>Men's</li>
                  <li>Men's</li>
                  <li>Men's</li>
                  <li>Men's</li>
            </ul>
        </li>
        
        <li class="top-right"><a href="#sign up">&#128722;My Order </a>
        </li>
        
        
      
      <li class="dropicon" ><a href="javascript:void(0);" onclick="dropMenu()" >&#9776;</a></li>
      </ul>        
        
 </nav>
        </div>
        
        <div id="slider">
            <ul>
                <li><img class="i" src="Image/slider2.png"></li>
                <li><img class="i" src="Image/slider1.jpg"></li>
                <li><img class="i" src="Image/slider3.jpg"></li>
            </ul>
       
        

            <!--dot-->
            <div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>
        </div>            
             
        
       <!--category section<mens,womens>--> 
        <div class="container">
            <div id="heading-block">
                <h2>Category</h2>
            </div>
            
            <!--category box-->
             <a href="project.html">
            <div class="catbox"> 
                 <img src="Image/cat2.jpg" alt="Men-fashion">
                 <span>Men Fashion</span>
                </div>
                </a>
            
            <a href="product-women.html">
            <div class="catbox"> 
                 <img src="Image/cat3.jpg" alt="Men-fashion">
                 <span>WOMen Fashion</span>
                </div>
                </a>
            
            <a href="Electronics.html">
            <div class="catbox"> 
                 <img src="Image/cat5.jpg" alt="Men-fashion">
                 <span>Electronics</span>
                </div>
                </a>
            
            <a href="gaming.html">
            <div class="catbox"> 
                 <img src="Image/cat6.jpg" alt="Men-fashion">
                 <span>Computer/Gaming</span>
                </div>
                </a>
            
            
             <!--category box end-->
            
        
            
        <!--Heading Category<product>--> 
          <div id="heading-block" >
              <h2>Products</h2>
          </div>
            <div class="prod-container" >
                <!--first products-->
                <div class="prod-box" >
                  <img src="Image/product1.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Man's special suit</p>  
                         <p style="color:#fff;font-weight:bold">price : $53</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                                <!--second products-->
                <div class="prod-box" >
                  <img src="Image/Product2.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>caual Men's shirt's</p>  
                         <p style="color:#fff;font-weight:bold">price : $20</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                                <!--third products-->
                <div class="prod-box" >
                  <img src="Image/Product3.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Women's special suit</p>  
                         <p style="color:#fff;font-weight:bold">price : $55</p>
                            <input  onclick="adcart()" type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                                <!--forth products-->
                <div class="prod-box" >
                  <img src="Image/Product4.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Special watches for men</p>  
                            <p style="color:#fff;font-weight:bold">price : $55</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                
                
                                <!--fifth products-->
                <div class="prod-box" >
                  <img src="Image/Product5.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Fastrack Watch for Men</p>  
                         <p style="color:#fff;font-weight:bold">price : $20</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                                                <!--fifth products-->
                <div class="prod-box" >
                  <img src="Image/Product6.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Fastrack Watch for WoMen</p>  
                         <p style="color:#fff;font-weight:bold">price : $25</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                                                <!--fifth products-->
                <div class="prod-box" >
                  <img src="Image/Product7.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Skybags</p>  
                         <p style="color:#fff;font-weight:bold">price : $30</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                                                <!--fifth products-->
                <div class="prod-box" >
                  <img src="Image/Product8.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Samgung Prime</p>  
                         <p style="color:#fff;font-weight:bold">price : $200</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                
                                                <!--fifth products-->
                <div class="prod-box" >
                  <img src="Image/Product9.jpg" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Spearkers</p>  
                         <p style="color:#fff;font-weight:bold">price : $30</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
                
                
                                                <!--fifth products-->
                <div class="prod-box" >
                  <img src="Image/Product10.png" alt="man suit">
                    <div class="prod-trans">
                        <div class="product-feature">
                        <p>Predator Asus</p>  
                         <p style="color:#fff;font-weight:bold">price : $200</p>
                            <input type="button" value="Add to cart">
                            
                        </div>
                    </div>
         
                </div>
            </div> 
           
            <div class="container">
                
                <div id="heading-block">
                    <h2>Offer</h2>
                </div>
                
                <div class="offer">
                    <a href="#"><img src="Image/offer1.png"></a>
                </div>
                
                 <div class="offer">
                    <a href="#"><img src="Image/special2.jpg"></a>
                </div>
                
                 <div class="offer">
                    <a href="#"><img src="Image/special3.jpg"></a>
                </div>
                
                 
            
            </div>
            
            
     </div>
        <div id="footer">
            <div class="container">
                
            
                <div class="footer_sub1">
                    <h2>our story</h2>
                    <p>This websites Today, it takes more than a pretty website to be successful.

Web design and digital marketing has come a long way in the last few years, and an SEO optimized website has gone from being a luxury, to an absolute necessity.Thank You For All Ur support.

<span><a href="https://thestorywebs.com/our-story/">read more. . . </a></span></p>
            </div>
              <!-- <div class="footer_sub2">
                    <center>
                        <h2>Importtant Links</h2>
                        
                        <ul>
                        
                        <li><a href="#">Home</a></li>
                         <li><a href="#">Home</a></li>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Home</a></li>
                            
                            
                        </ul>
                    </center>
            </div>--> 
               
                 <div class="footer_sub2">
                    
                        <h2>Social Links</h2>
                        
                        
                       
                     <a  class="btn" href="">
                        <i class="fab fa-twitter"></i>
                    </a>
                     <a  class="btn" href="">
                        <i class="fab fa-google"></i>
                    </a>
                     <a class="btn" href="">
                        <i class="fab fa-instagram"></i>
                    </a>
                     <a class="btn" href="">
                        <i class="fab fa-youtube"></i>
                    </a>
                    
            </div>
               
                
                
                <div class="footer_sub3">
                    <center>
                    <h2> subscribe us</h2>
                        <form method="POST" name="regno" onsubmit='return sub()'>
                        <input type="text" name="email"  value="" placeholder="Write your E-mail" id="input1" >
                     <input type="submit" name="submit_btn" value="subscribe"  class="sub1" required>
                        <p class="par">Enter your E-mail id for notifaction by us</p>
                        </form>
                    
                    </center>
                </div>
                <!--Social button-->
                
            </div>
        </div>
        </div>
 
<script>
/*var myIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("i");
    var y=document.getElememntsByClassName("dot");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 2000); // Change image every 2 seconds
}*/
    var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("i");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1} 
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none"; 
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block"; 
  dots[slideIndex-1].className += " active";
}
</script>
    
    <script>
        var price=$(document).attr()
    </script>
    
    <!--script for nav part-->
     <script>
        
        function dropMenu(){
            var x=document.getElementById("dropclick");
            if(x.className === "top"){
                x.className += " responsive";
/* change top to top.responsive  */
                
         }
            else{
                x.className="top";
                
            }
        }
        
 </script> 
    
   
    <script type="text/javascript">
		

		function sub(){

		
			var email=document.forms["regno"]["email"];

			if(email.value=="")
			{
				alert("email field is blank");
                    return false;
			}


			 else if(email.value.indexOf("@",0)<0)
			{
				alert("@ symbol missing");
				return false;
			}
             else if(email.value.indexOf(".com",0)<0)
			{
				alert(".com symbol missing");
				return false;
			}
			 



		
      alert("You are Now subscribed to our websites");
  }

	</script>
    
    
    <script>
       
    </script>
    
</body>
</hmtl>



/*Sign In PAGE*/

<!DOCTYPE html>
<html>
	<head>
		<title>SignUp</title>
		<link href="css/signup.css" rel="stylesheet" type="text/css">
		<script src="jquery.js"></script>
		<script>
			function checkForm(){
			var Fname=document.forms["regno"]["fname"];
			var Lname=document.forms["regno"]["lname"];
			var Email=document.forms["regno"]["email"];
			var ph=document.forms["regno"]["num"];
			var password=document.forms["regno"]["Password"];
			if(Email.value.indexOf("@",0)<0)
			{
				alert("@ symbol missing");
				return false;
			}
			 if(ph.value == "")
			{
				alert("phone number field is blank");
				return false;
			}
			 if(password.value == "")
			{
				alert("please Enter Your Password");
				return false;
			}
			alert("form submitted");
			return true;
		}
	</script>
</head>
	<body >
		<div class="simple-form">
			<form class="registration" onsubmit="return checkForm()" action="home.html" method="post" name="regno" >
				<h2>Sign-Up Form</h2>
				<input type="text" name="fname" id="button" placeholder="Enter Your FirstName" required><br><br>        
				<input type="text" name="lname" id="button" placeholder="Enter Your LastName" required><br><br> 
				<input type="email" name="email" id="button" placeholder="Enter Your EmailId" required><br><br> 
				<input type="password" name="Password" id="button" placeholder="Enter Your Password" required><br><br>
				<select type="text" id="phone"><option>+91</option></select>		
				<input type="number" name="num" id="ph" placeholder="Enter Your PhoneNumber" required><br><br>		
				<input type="radio" name="gender" id="rd"><span id="but">Male</span><input type="radio" name="gender" id="rd"><span id="but">Female</span><br><br>
				<input type="submit" value="SignUp" id="butt">             
			</form>
		</div>
	</body>
</html>


/*css for Home Page*/



    #wrapper
{
    font-family:tahoma;
   
}
.container
{
    width:100%;
    max-width:1280px;
    margin:0 auto;
}
#subheader
{
    width:100%;
    height:30px;
    background-color:rgb(221, 68, 68);
    color:azure;
    margin-top: -15px;
}
#subheader p
{
    float:left;
    margin-top: 7px;
}
#subheader a
{
    float:right;
    line-height:30px;
    color:aliceblue;
    margin-left:30px;
    text-decoration: none;
    margin-left:30px;
}
#main-header{
    width:100%;
    height:100px;
    background:rgb(244, 63, 63);
    float:left;
    margin-top:-15px;
    
}
#logo{
    width:250px;
    margin-top:10px;
    float:left;
    
}
#ist
{
    color:cornsilk;
    font-size:45px;
    font-weight:bold;
    margin-left:15px;
    font-family:cursive;
}
#iist
{
    color:cornsilk;
    font-size:35px;
    font-weight:bold;
    margin-right:30px;
    font-family:cursive;
}
#search
{
    width:650px;
    float:left;
    padding:20px;
    margin-left:10px;
}
.search-area
{
    width:650px;
    height:50px;
    background:#fff;
    border:none;
    border-radius: 10px;
    float:left;
    padding-left:15px;
    box-shadow: 2px 3px 8px black;
  
}

.search-btn
{
    width:100px;
    height:50px;
    border-radius:10px;
    border:none;
    color:#fff;
    background:brown;
    margin-right:-400px;
    cursor:pointer;
    
}
#user
{
    width:300px;
    float:right;
    margin-top:20px;
}

#user li
{
    float:left;
    width:140px;
    margin-left:-10px;
    text-align:center;
    list-style:none;
    font-size:25px;
   
}
#user li:hover{
    font-size:30px;
    transition:all .5s ease;
}
#user li a{
    color:white;
    text-decoration:none;
}
/*#navigation{
    width:100%;
    height:30px;
   background:rgb(244, 63, 63);
    float:left;
    box-shadow:10px 14px 50px grey;
    
}
nav{
    width:1280px;
    margin:0 auto;
}
nav a
{
    margin-left:35px;
    color:white;
    text-decoration:none;
    
}
nav a:hover
{
 
    color:darkmagenta;
    transition:all .7s ease;
    
}*/
#navigation{
    width:100%;
    height:30px;
   background:rgb(244, 63, 63);
    float:left;
    box-shadow:10px 14px 50px grey;

}

nav{
    width:100%;
    margin:0;     /* edge to edge */
    
    
}

nav ul
{
    
    background-color:rgb(244, 63, 63);
    overflow:hidden;
    margin:0;
    padding: 0;
}

 nav ul.top li {
    list-style: none;
    float:left;
    
}
nav ul.top li.top-right{
    float: right;
}

nav ul.top li a{
    text-decoration:none;
    display: block;
/* same as below font-size:16px;*/
    min-height: 16px;   /*shrink */
    text-align: center;
    padding: 14px;
    text-transform: uppercase;
    color:white;
       
}
a{
    transition: 0.5s;
}

nav ul.top li a:hover{

    background-color:#2d7979;
    color:white;
  transform: scale(1.0);
    transition: transform 1000ms ease-in-out;
    
/* transform: rotate(20deg);

  //  transform: rotateX(360deg);
   //  transform: rotatey(95deg);
    font-size: 18px;*/
    
}
ul.top li.dropicon
{
    display: none;  /* hide unicode from dekstop*/
}

.dropclick {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {background-color: #f1f1f1}

.dropdown:hover .dropdown-content {
    display: block;
}

.dropdown:hover .dropbtn {
    background-color: #3e8e41;
}

@media screen and (max-width:680px){
    
  ul.top li:not(:nth-child(1))   {
        
        display:none;  
    }
    
  ul.top li.dropicon 
    {
        display:block;
        float:right;
     }
    
    ul.top.responsive li.dropicon{
        position:absolute;
        top:0;
        right:0;
        
    }
    
/*  still inherit all previou <a> properties ,lets change */

    ul.top .responsive{
        position:relative;
    } 
    ul.top.responsive li{
        display:inline;
        float:none;
    }
    ul.top.responsive li a{
        display:block; 
        text-align: left;
    }
    
    
    
}


/*slider*/
#slider img{
    
    width:100%;
    height:60%;
    
    
}
#slider {
    width:100%;
    max-width:100%;
    float:left;
    margin-top: 3px;
    position: relative;
}
#slider ul{
  list-style:none;
   margin-left: -40px;
    
    
    
}
/*category*/
#heading-block
{
    width:100%;
    height:auto;
    float:left;
    color:rgb(221, 68, 68);

    font-size:22px;
}
#heading-block h2
{
    
    line-height:35px;
    border-left:20px solid brown;
    padding-left:10px;
}
.catbox{
    width:235px;
    height:235px;
    float:left;
    overflow:hidden;
    position:relative;
    margin:0 15 30 ;
    
    
}
.catbox span{
    width:100%;
    height:35px;
    line-height: 35px;
    background:rgba(0,0,0,0.6);
    color:white;
    display:block;
    bottom:30px;
    position:absolute;
    z-index:999;
    text-align:center;
    
}
.catbox:hover span
{
    color:aqua;
}
.catbox img
{
    max-width: :100%;
    transition:all .5s ease;
}
.catbox:hover img
{
    transform:scale(1.3,1.3);
    transition:all .5s ease;
}
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
    margin-top:-300;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
   
  transition: background-color 0.6s ease;
   
}
.active, .dot:hover {
  background-color: #717171;
}
  /*products css*/
.prod-box
{
    width:235px;
    height:290px;
    overflow:hidden;
    float:left;
    margin:0 10 30 0;
    position:relative;
}
.prod-box>img{
    max-width:160%;
}
.prod-trans{
    background:rgba(0,0,0,0.6);
    width:100%;
    height:100%;
    top:0;
    left:0;
    bottom:0;
    right:0;
    position:absolute;
    opacity:0;
   transition: all .5s ease;
}
.prod-box:hover .prod-trans{
    opacity: 1;
    transition: all .5s ease;
}
.product-feature
{
    text-align: center;
    margin-top:-150px;
    transition: all .5s ease;
    
}
.product-feature p
{
    color:#00eb00;
    font-family:verdana;
}
.prod-box:hover .product-feature{
    margin-top:150px;
    transition: all .5s ease;
}
.product-feature input
{
    width:150px;
    height:35px;
    font-size:17px;
    
}
.offer
{
    width:420px;
    float:left;
  
    margin-right:10px;
}
.offer:last-child{
    margin-right:0px;
}
.offer img
{
    width:100%;
}

#footer
{
    width:100%;
    height:300px;
    background:#f5f5f5;
    float:left;
}
.footer_sub1
{
    width:25%;
    float:left;
}

.footer_sub2
{
    width:20%;
    float:left;
list-style:  none;
    
    
}

.footer_sub2 ul li
{
    list-style:none;
}
.footer_sub2 ul li a
{
   text-decoration:none;
    color: black;
}
.footer_sub2 ul li a:hover{
    color:#1aaa1a;
    text-decoration:underline;
}

.footer_sub3
{
    width:35%;
    float:left;
}
    
#input1
{
    width:350px;
    border:none;
    height:50px;
    padding:15px;
    float:left;
}
.sub1
{
    height:50px;
    border:none;
    background:orange;
    float:left;
}
.par
{
    color:#999;
    font-style:italic;
    font-size:14px;
    
}


/*social*/
.footer_sub2
{
    
    transform: translate(-3%);
    width:30%;
    text-align: center;
    
    
    }
.btn
{
    display: inline-block;
    width:50px;
    height:50px;
    background:#f1f1f1;
    margin:5x;
    border-radius:30%;
    box-shadow:0 5px 5px -5px #00000070;
    color: #3498DB;
    overflow: hidden;
    position: relative;
    
}
.btn i
{
    line-height:50px;
    font-size:13px;
    transition: 0.2s linear;
}
.btn:hover i
{
    transform: scale(1.3);
    color:#f1f1f1;
    
    
}
.btn::before{
    content:"";
    position:absolute;
    width:120%;
    height:120%;
    background:#3498DB;
    transform: rotate(50deg);
    left:-110%;
    top:30%;
    overflow: hidden;
}
.btn:hover::before{
    animation:aaa 0.7s 1;
    top:-10%;
    left:-10%;
    
}
@keyframes aaa{
    0%{
        left:-110%;
        top:90%;
    }
     
     50%{
        left:10%;
        top:-30%;
    }
     100%{
        left:-10%;
        top:-10%;
    }
}


/*CSS FOR SIGN IN PAGE*/

body{
	background-image:url(images/sign.png);
	background-repeat:no-repeat;
	background-size:100%;
}
h2{
	font-family:Rockwell;
	color:white;
	font-weight:500;
}
.simple-form{
	text-align:center;
	margin: 50px 450px;
}
.registration{
	width:100%;
	background-color:#051019;
	opacity:0.8;
	padding:50px 0px;
	border-radius:5px;
	box-shadow:4px 6px 8px grey;
}
#button{
	width:250px;
	padding:10px;
	border-radius:5px;
	outline:0px;
}
#ph{
	width:180px;
	padding:10px;
	border-radius:5px;
	outline:0px;
}
#butt{
	width:250px;
	padding:10px;
	border-radius:5px;
	outline:0px;
	background-color:#0c6996;
	border:2px solid #01010c;
	color:aliceblue;
	font-size:19px;
}
#phone{
	width:65px;
	padding:10px;
	border-radius:5px;
	outline:0px;
}
#after{
	width:100%;
	background-color:#051019;
	opacity:0.8;
	padding:50px 0px;
	border-radius:5px;
	box-shadow:4px 6px 8px grey;
}
#but{
	color:white;
	font-size:19px;
}
