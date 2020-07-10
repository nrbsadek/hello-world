<!DOCTYPE html>
<html lang="en">
<head>
   <title> School Mailing </title>
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Services block</title>
    <!-- Google fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Metal+Mania&display=swap" rel="stylesheet">
    <!-- fontawesome.com-->
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
    <!-- Core Css -->
    <link rel="stylesheet" href="./css/style.css" type="text/css">
    <style>
    *{
			margin:0px;	
			padding:0px;
			box-sizing: border-box;
			font-family : sans-serif, roboto;
			
			
				}
				
.head-bar{
				background:#6495ED;
				display: flex;
				margin: 7px;
				width:100%;
				padding :0px;
		
				}
				
.text{
				display: inline-block ;
				float:right;
				width:70%;
				margin: auto;
				}
				
.text-1{
				color: #e3edf7;
				font-size: 13px;
				float:right;
				margin-left: 8px;
				align-items: center;
				justify-content:center;
				font-weight:400;
				}
		
	.text-1 	i {
    color: #64ff2e;
    text-align: center;
    }
		
	#social{
					width:30%;
					float:left;
					}
#social i {
				/*width:20px;
				height:20px;*/
    text-align: center;
    border-radius: 5px;
    background : white;
    padding: 5px;
    margin: 10px ;
    transition:.5s all;
    
    }
 .fa-facebook-square{
				color :#3b5998;
				}
				
.fa-twitter-square{
				color :#00acee;
				}
				
.fa-instagram-square{ 
				color :#ff1700;
				}
/* navigation & header */
.mainContainer{
				
				background: url('../img/images.jpg') no-repeat;
  background-position: center;
  background-size: cover;
  text-align:center;
  margin: auto;
  overflow: hidden ;
 }
.mainContainer .header{
				
background: #282d4a;
margin: auto;
position:sticky;
top:0;
 
}

#logo{
				text-transform :capitalize;
				font-size :20px;
				float:left;
				margin :10px 10px;
				padding :10px 10px;
				color:white;
				}
				

#logo_1{
				color:coral;
				
				}
#logo_2{
				color:#6495ed;
				}


.header ul{
float:right;
padding :10px;
height:0px;}

.header ul li {
display: inline-block ;
overflow:hidden;
margin: 10px 10px;
text-transform : capitalize ;
padding:10px;
transition: all 1s;
float:left;
margin-bottom:20px;
}

.header ul li a{
text-decoration:none;
font-size: 15px;
color: #1777ff ;
font-weight:bold;
padding:0px;
transition :  all 1s;
}

.header ul li:hover{
border-bottom:3px solid yellow ;
border-radius:3px;
}

.header ul li:hover a{
				color:#fff;
				}
/* showcase */

#showcase{
				overflow: hidden;
				margin: auto; 
				
				}

.container{
			/*
				min-height:400px;
  background: url('../img/images.jpg') no-repeat;
  background-position: center;
  background-size: cover;
  text-align:center;
  margin: auto;
  overflow: hidden ;
  */
				}
#showcase, .container h1 {
  margin-top:90px;
  font-size:60px;
  margin-bottom:40px;
  text-align :center ;
  color: #ffe55d ;
  
}

#showcase p{
		padding :10px;
  font-size:20px;
  margin:auto;
  color: #fff;
}

#content{
				text-align:center;
				background: #f1f1f1;
				padding:10px;
				margin: auto;
				}
#content h4{
				font-size:20px;
				margin:10px;
				padding:10px;
				color:#6495ed;
				}
				
#content p{
				text-size:15px;
				margin-bottom:10px;
				color:#444;
				}
.btn{
				width:130px;
				padding:8px;
				color:white;
				font-size: 14px;
				background:#6495ed;
				font-weight:500;
				text-transform:capitalize;
				border-radius:5px;
				
				transition: all .6s;
				}

.btn:hover{
				background:coral;
				color:white;
				}			

.border{
display:block;
width:40px;
height:3px;
margin:auto;
background:#282d4a;
margin-bottom:10px;

}

#inputFiled{
				width:100%;
				background:#e3edf7;
				padding:20px;
				margin:10px;
				display:inline-flex;
				align-items:center;
			justify-content: center;
				
				}
				
#inputFiled input{
				width:25%;
				border-radius:5px;
				padding:10px;
				margin:7px;
				
				}

#aside{
				max-width:1200px;
				overflow: hidden;
			 
				}
#aside h4{
				text-align: center;
				color: #6495ed;
				font-size:30px;
				margin:10px 10px;
				}
				

.wrapper{
				width:30%;
				min-height:300px;
				padding:10px;
				margin:10px 10px;
				display:inline-block;
				overflow: hidden ;
				box-shadow: -3px 4px 8px rgba(0,0,0,0.4);
				transition: .6s all;
				text-align: center;
				}				
	
.wrapper img{
				width:150px;
				height:150px;
				margin: auto;
				margin-top:5px;
				display:block;
				
				}
.wrapper h5{
				margin-top:10px;
				margin-bottom: 10px;
				color: #362eff;
				}

.wrapper p{
				text-size: 10px;
				opacity:0;
				transition: .6s all;
				
				}

.wrapper:hover{
				transform: translateY(-5px);
				background :#ffdda2;
						
				}
.wrapper:hover p{
				opacity:1;
				}

#row{
				text-align:center;
				}
			
		/* team section */
#team-section{
				max-width:1200px;
				text-align:center;
				background:#ffe8e8;
				overflow:hidden;
				min-height:400px;
				margin-top:20px;
				}
				
#team h4 {
				font-size:30px;
				color:#6495ed;
				text-align:center;
				margin-top: 10px;
				}
				
	.p-info{
					width:30%;
					height:300px;
					background :white;
					display:inline-block ;
					padding: 20px;
					margin:10px;
					box-shadow: 3px 3px 8px rgba(0,0,0,0.2);
					transition: .6s all; 
					}
					
			.p-info:hover{
							background : #e3edf7;
							transform: translateY(-7px);
							}
		.p-info:hover >img{
						transform: translateY(-7px);
						box-shadow: -3px 3px 8px rgba(0,0,0,0.3);
						filter: none;
						border-radius: 0px;
						background : #6495ed;
						}
						
		.p-info:hover i{
						opacity:1;
						}
	.p-info h5{
					margin-top :7px;
					color: #2f3542;
					text-transform: uppercase ;
					}
	.p-info p{
					text-style:italic;
					color:green;
					margin-top:7px;
					margin-bottom:10px;
					}
.p-info img {
				width:120px;
				height: 120px;
				padding: 3px;
				border-radius: 50%;
				filter: grayscale(100%);
				transition : .3s all;
				
				}
				
				
				
	.sm{
					padding:5px;
					margin:auto;
					align-items:center;
					justify-content: center;
					
					}
					
	.sm i{
    color: white;
    background: #282d4a;
    text-align: center;
    border-radius: 50%;
    padding: 5px;
    margin: 10px ;
    transition:.5s all;		
    opacity: 0;			
					}
					
	.sm i:hover {
					transform: scale(1.3);
					}
					
					
					
/* about us */

.about-section{
				width:100%;
				background: #ddd;
				padding: 0px;
				overflow: hidden; 
				}
	
	
	
.wrap-text{
				background: url('../img/about.jpg') no-repeat left;
				background-size:56%;
				background-color: #fdfdfd;
				padding: 100px 10px; 
			 overflow: hidden; 
			 margin: 7px;
			 position: relative;
				}			
				
.wrap-text h4{
			font-size:30px;
				color:#6495ed;
				padding : 7px 0;
				position: absolute;
				top: 25%;
				left: 51%;
				}
/*
.wrap-text >p{
				width: 57%;
				float: right;
				background : #fdfdfd;
				padding:70px ;
				overflow: hidden;
				margin-top  : 20px;
				padding-top: 10px;
				position: relative;
				}
		*/
		.text-p{
						font-size: 14px;
						padding: 40px;
						color: #545454;
						line-height: 25px;
						margin-top: 20px;
						}		
						.divText{
										background : #fdfdfd;
										width: 55%;
										float:right;
										padding : 20px;
										}
										


/* contact details */


.article{
width:100%;
height:400px;
overflow: hidden ;
display :flex ;
margin-bottom: 20px;
}

.article h2{
				color:#6495ed;
				font-size: 30px;
				margin-left: 190px;
				padding : 8px;
				
				}
.article h1 {
text-align:center;
color: #6495ed;
}
.flex{
				width:60%;
				float:left;
				overflow: hidden; 
				margin-left: 20px;
				}
.aside{

width:35%;
float: right;
background: #282d4a;
overflow:hidden;
margin-top : 55px;
margin-bottom :10px;
border-radius :5px;
}

#inputFiled2{
width:70%;
display:block;
border: 1px solid #333;
padding :10px;
padding-bottom: 10px;
overflow: hidden;
margin-top : 10px;
border-radius: 3px;
margin : 10px 50px;
}


#btn{
overflow : hidden;
display: block;
background : #2196f3;
color: #fff;
font-weight: bold;
margin: 20px 50px ;
padding:5px;
border-radius : 3px;
}

#btn:hover{
background: #2196f3;
color: #fff;
box-shadow : 0 0 10px #2196f3, 0 0 40px  #2196f3, 0 0 80px #2196f3;
transition:.2s all;
transtition-delay: 1s;
border:none;}



	/* footer */

.footer{
				width: 100%;
text-align: center;
text-transform:capitalize;
font-size:20px;
background: #6495ed;
padding:30px;
color:#fff;
overflow: hidden; 
}
		
/* Responsive section */

@media screen and (max-width:900px){
				#social {
								width:50%;
								}
				#navInner {
								
								width:50%;}
								
						.header{
										width:50%;
										}	
										
							#showcase .container {
											width:50%;
											}
								.border{
												width:50%;
												}
												
										#inputFiled input{
														width:50%;
														}
														
											#aside .wrapper {
															width:50%;
															
															}
															
										.p-info{
														width:50%;
														}
									.about-section, wrap-text{
													width:50%;
													padding: 10px;
													}
				}
				
				
@media screen and (max-width:500px){
				#social {
								width:100%;
								}
				#navInner {
								
								width:100%;}
								
						.header{
										width:100%;
										}	
										
							#showcase .container{
											width:100%;
											
											}
								.border{
												width:50%;
												}
												
										#inputFiled input{
														width:100%;
														}
														
											#aside .wrapper {
															width:100%;
															
															}
															
											.container h1{
															font-size:40px;
															
															}
															
									.p-info{
													width:100%;
													}
													
									.about-section, wrap-text{
													width: 100%;
													padding: 10px;
													}
				}

    
    
    </style>
    
   
    
</head>
<body>
<!--Social icon bar-->
<div class="head-bar">
<div id="social">
<i class="fab fa-facebook-square" aria-hidden="true"></i>
<i class="fab fa-twitter-square" aria-hidden="true"></i>
<i class="fab fa-instagram-square"></i> 

</div>

<div class="text"> 
<span class="text-1"> <i class="fa fa-envelope"></i> schoolmailing@gmail.com</span>
<div class="text">

<span class="text-1"><i class="fa fa-phone-square"></i> +8801700000000</span>
</div>
</div>
</div>

<!--Nav-bar & logo  -->
<section class="mainContainer">
<header class="header">
<a href="#">
<h1 id="logo"> <span id="logo_1"> School </span> <span id="logo_2"> Mailing</span>  </h1> </a>
<ul> <li class="active"> <a href="#">home</a></li>
 <li> <a href="#">about us </a></li>
<li> <a href="#">services </a></li>
 <li> <a href="#">Education insights </a></li>

 <li> <a href="#"> get a quote </a></li>



</ul>

</header>
<section id="showcase">
<div class="container">
<h1> We Ensure Better Education for A Better World! </h1>
<p>We supply industry loading education data, design  and send eye-catching emails , and deliver  postal mall campaign  to UK School  Choose  from over 433,000 Named Teachers and Decision  Makers </p>

<button class="btn"> Our Services  </button>

<button class="btn"> Get a quote </button> 
</div>

</section>
</section>
<section id="article">
<div id="content">
<h4>
Get your Free 2020 Marketing to Schools Pack </h4>
<div class="border"></div>
<p> Boost your markting with our Ten-Step Marketing Plan, UK Term Dates Guides, Marketing to Schools Top Trends and more! </p>
</div>
<div id="inputFiled">
<form post="action">
	<input type="text" placeholder="Your Name" name="uname" id="userName" required>
	<input type="text" placeholder="Your E-mail Address" name="eadd" id="userName" required>

		<input type="text" placeholder="Your Company" name="cname" id="userName" required>
 
	<button class="btn"> <i class="fa fa-download"></i> Download</button>

</form>
</div>
</section>
<section id="aside">
<h4>Our Services </h4>
<div class="border"></div>
<div class="wrapper">
<img src="./img/1.jpg" alt="image">
<h5>Accurate Schools Data</h5>
<p>Data for UK Schoos, teachers and named decision makers supplied with teeth time updates to support your marketing
</p>
</div>
<div class="wrapper">
<img src="./img/2.jpg" alt="image">
<h5>School & Teacher Email Campaigns</h5>
<p>Target ovet 433,000 named teachers and decision Schools

</p>
</div>
<div class="wrapper">
<img src="./img/3.png" alt="image">
<h5>Direct Postal Campaigns </h5> <p>Print, mail and fulfillment services for UK Education Supplies

</p>
</div>
<div id="row"> <button class="btn"> See all Services </button></div>


</section>
<!-- team section -->
<div id="team-section">
<div id="team">
<h4>Meet our team</h4>
<div class="border"></div>
</div>
<div class="p-info">
<img src="./img/p1.png">
<h5> Muhammad Sadek </h5>
<p class="des">CEO & Founder </p>
<div class="sm">
<a href="#"><i class="fab fa-facebook-f"></i></a>
<a href="#"><i class="fab fa-twitter"></i></a>
<a href="#"><i class="fab fa-instagram"></i></a>
</div>

</div>

<div class="p-info">
<img src="./img/p2.jpg">
<h5> Mohammad Ullah </h5>
<p class="des"> Professor  </p>
<div class="sm">
<a href="#"><i class="fab fa-facebook-f"></i></a>
<a href="#"><i class="fab fa-twitter"></i></a>
<a href="#"><i class="fab fa-instagram"></i></a>
</div>
</div>

<div class="p-info">
<img src="./img/ps.png">
<h5> MD Sujon </h5>
<p class="des"> Lecturer  </p>
<div class="sm">
<a href="#"><i class="fab fa-facebook-f"></i></a>
<a href="#"><i class="fab fa-twitter"></i></a>
<a href="#"><i class="fab fa-instagram"></i></a>
</div>
</div>


</div>

<!-- About us -->

<div class="about-section">

<div class="wrap-text">
<h4> About Us </h4>
<div class="divText">
<p class="text-p">Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus velit ducimus enim irventore earum, eligendi nostrum pariatur necessitatibus eius dicta a voluptates sit deleniti autem error eos totam nisi neque valuptates sit deleniti autem error eos totam nisi neque</p>
</div>
</div>
</div>
<!-- Contact address below -->
<!-- contact us-->
<section class="contact-details">
<div class="article">
<div class="flex">
<h2> Google Map</h2>
<iframe width="100%" height="300" frameborder="1" scrolling="no" marginheight="3" marginwidth="3" src="https://www.google.com/maps/embed/v1/view?key=AIzaSyAJifc7pwvUkN0yrtn7BPn8I-lRg33PSNc&center=23.0186111,91.41&zoom=12&maptype=default" style="border:1px solid #ddd;"></iframe>
</div>
<div class="flex aside">
<h1> Get a Quote  </h1>
<span class="border"> </span>
<form action="post">
<input id="inputFiled2" type="text" placeholder="Name" required>
<input id="inputFiled2" type="email" placeholder="E-mail"required >
<input id="inputFiled2" type="text" placeholder="Subject" required>
<textarea id="inputFiled2" type="text" placeholder="Message" required>
</textarea>
<button id="btn" type="Submit"> Submit
</button>
</form>
</div>
</div>
</section>
<!--footer-->
<div>
<footer class="footer">

<p> &copy; 2020 All rights reserved 
</p>
</footer>
</div>
</body>
</html>
