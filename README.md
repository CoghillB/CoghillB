<!DOCTYPE html>
<html>
<head>
   <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  </head>
  <title>Product Landing Page</title>
  <!--START OF PAGE-->
  <header id="top-header">
  <div class="container">
    <img id="header-img" src="https://spillwords.com/wp-content/uploads/2015/02/Conquer-or-Conquered-spillwords.jpg" />
    <!--START OF NAVBAR-->
    <nav id="nav-bar">
      <ul>
        <li> <a class="nav-link" href="#Info">Info</a></li>	        
        <li><a class="nav-link" href="#Tips_&_Tricks">Tips & Tricks</a></li>
        <li><a class="nav-link" href="#Shop">Shop</a></li>
      </ul>
    </nav>
    <!--END OF NAVBAR--> 
        </div>
        </header>
        <!--EMAIL SUBMITTION-->
        <form id="form">
        <div id="email-form">
        <div id="email-label">
        <label for="email" id="coghill_fitness">Coghill Fitness</label>
        </div>
        <input id="email" type="email" placeholder="Enter Email to Register">
        </input>
        </div>
        </form>
        <!--END OF EMAIL-->
        <!--START OF INFO SECTION-->
        <section class="info" id="Info">
        <div id="section-header"><header class="info_header">Info<header></div>
        <div id="info" class="row">
			<div class="column left"><img src="/Users/braydencoghill/Documents/Coding/HTML:CSS/icons8-gym-50.png" alt="Logo."/></div>
			<div class="column right"><p><span id="span">About Me</span> - I was born and raised in Saskatoon, Sk where I played sports all throughout my childhood. After I stopped playing sports my health really got away from me. Fast forward 4 years and I decided to was time to get back in shape. I fell back in love with fitness and now plan on competing in Body Building in the end of 2023. I've been that person who isn't happy with their health and I can relate to anyone going through the same thing.</p>
			</div>
			</div>
		<div id="info" class="row">	
			<div class="column left"><img src="/Users/braydencoghill/Documents/Coding/HTML:CSS/icons8-gym-50.png" alt="Logo." />
			</div>
			<div class="column right"><p><span id="span">Training & Nutrition</span> - Nutrition and exercise not only complement each other but they need each other. Even if you eat a perfectly balanced diet you need to exercise to burn the calories. You also need to exercise to strengthen your muscles, heart, and lungs. Food gives you energy, and you need energy to exercise.</p>
			</div>
			</div>
			<div class=row>
			 <div class="column left"><img src="/Users/braydencoghill/Documents/Coding/HTML:CSS/icons8-gym-50.png" alt="Logo."/>
			 </div>
				<div class="column right"><p><span id="span">Why you Should Hire a Coach</span> - A personal trainer can give you the tools and support that you need to reach a health and fitness goal. They can provide support, accountability, education, and a personalized plan of attack, so you may find working with one well worth the investment.</p></div>
				</div>
			 </section>
			 <!--END OF INFO SECTION-->
			 <!--START OF VIDEO-->
			 <div class="video" id="Tips_&_Tricks">
        <header id="section-header" class="youtube">Tips & Tricks</header>
        <iframe id="youtube" width="450" height="315" src="https://www.youtube.com/embed/QzsIwakqQSA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    		</div>
			 <!--END OF VIDEO-->
			 <!--START OF SHOP-->
			 <div class="row1">
			 <header id="section-header">Shop</header>
			 <div class="column1">
			 <div class="top-box">
			 <header id="Shop" class="nutrition" id="options">Nutrition</header></div>
			 <p id="price">$130</p>
			  <p id="description">This will get you a custom meal plan to follow with exact macros, food suggestions, and suppliment/vitamine suggestions.</p>
			  <div id="button">
			  <button class="submit">
        <a id="enter" href="https://freecodecamp.org">SUBMIT</a>
        </button>
        </div id="button">
			  </div>
			  <div class="column1">
			 <div class="top-box">
			 <header class="training" id="options">Training</header></div>
			  <p id="price">$150</p>
			  <p id="description">Training program made specifically for your body and your goals.</p>
			  <div id="button">
			   <button class="submit">
        <a id="enter" href="https://freecodecamp.org">SUBMIT</a>
        </button>
        </div>
			   </div>
			   <div class="column1">
			  <div class="top-box">
			 <header class="nutrition-training" id="options">Nutrition + Training</header></div>
			  <p id="price">$250/Month</p>
			  <p id="description">This is the best bang for your buck. You get personalized nutrition and fitness programs, on-going coaching with weekly check-ins.</p>
			  <div id="button">
			  <button class="submit">
        <a id="enter" href="https://freecodecamp.org">SUBMIT</a>
        </button>
        </div>
			  </div>
			  </div>
			 <!--END OF SHOP-->
			 <!--START OF FOOTER-->
		<section>
		<footer>
		    <p><a id="enter" href="#nav-bar">Back to Top of Page</a></p>
			<p><a id="enter" href="nav-bar">Terms and Conditions</a></p>
			<p>Copyright 2024, Coghill Development</p>
		 </footer>
			</section>
     </html> 
     
     *{
margin: auto;
scroll-behavior: smooth;
font-family: ariel, sans-serif;
}

#top-header {
background: black;
margin: 0;
font-family: sans-serif;
font-weight: 400;
width: 100%;
height: 120px;
}

#header-img {
float: left;
max-width: 20%; 
margin-top: 13px; 
margin-left: 0%;
background-size: cover;
height: 85px;
}


.container{
width: 80%;
margin: 0 auto;
height: 95px;
z-index: 1;
}

#nav-bar{
float: right;
}

nav ul{
margin: 0;
padding: 0;
list-style: none;
}

nav li{
display: inline-block;
margin-left: 70px;
margin-top: 45px;
}

nav a {
color: #f6f8fa;
text-decoration: none;
text-transform: uppercase;
font-size: 16px;
}

nav a:hover{
color: red;
}

body{
background-color: #f6f8fa;
}

.list{
margin: 0 auto;
display: table;
padding: 15px;
}

form{
padding: 10px;
margin: 35px;
text-align: center;
font-weight: 300;
}

#coghill_fitness{
font-family: impact, sans-serif; 
font-size: 30px;
height: 60px;
text-transform: uppercase;

}

input{
width: 30%;
text-align: center;
box-shadow: 12px 12px 8px black; 
}

#email-label{

color: black;
font-weight: 900;
padding: 15px;
margin-bottom: 10px;
}



#section-header{
text-align: center;
text-transform: uppercase;
margin-top: 30px;
padding: 25px;
padding-bottom: 25px;
font-size: 22px;
}

.row {
  display: flex;
  width: 65%;
}

.column {
  flex: 50%;
  padding: 23px;
}


.video{
padding: 25px;
margin: auto;
max-width: 450px;
}

.top-box{
border: 1px solid grey;
padding: 10px;
max-width: 400px;
width: 300px;

text-align: center;
background-color: black;
border-left: 3px solid grey;
border-right: 3px solid grey;
border-top: 3px solid grey;
}

#options{
max-width: 100%;
color: #f6f8fa;
height: 30px;
max-height: 30px;
}

#price{
padding: 10px;
padding-bottom: 50px;
max-width: 400px;
width: 300px;
border-left: 3px solid grey;
border-right: 3px solid grey;

text-align: center;
font-size: 20px;
font-weight: 500;
}

#description{
border-left: 3px solid grey;
border-right: 3px solid grey;
padding: 10px;
max-width: 400px;
width: 300px;
height: 100px;

text-align: center;
text-decoration: none;
font-weight: 100

}



.submit{
display: block;
margin-top: 30px;
width: 50%;
padding: 15px;
font-size: 15px;
background: black;
border: 3px solid #3b3b4f;
color: #f6f8fa;
box-shadow: 5px 8px;

}

#button{
border-left: 3px solid grey;
border-right: 3px solid grey;
border-bottom: 3px solid grey;
color: #f6f8fa;

padding: 10px;
max-width: 400px;
width: 300px;
}

#enter{
color: #f6f8fa;
}

#enter:hover{
color: red;
}

.shop{
display: block;
text-align: center;
padding-bottom: 35px;
}


.column1 {
  float: left;
  width: 33.33%;
  height: 300px;
}


/* Clear floats after the columns */
.row1:after {
  content: "";
  display: table;
  clear: both;
}

footer {
  margin-top: 120px;
  margin-bottom: 0;
  padding-top: 40px;
  padding-bottom: 40px;
  padding-right: 25px; 
  width: 40%;
  height: 15px;
  
  text-align: right;
  color: #f6f8fa;
  background-color: black;
  
}

footer a{
color: #f6f8fa
}

@media only screen and (max-width: 550px) {
  .column1 {
    font-size: 6rem;
  }









