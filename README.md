# sahil

<html>
	<head>
		<title>My First HTML Page</title>

		<meta name="viewport" content="width=device-width, initial-scale=1.0">

		<style>
		* {
			margin: 0;
			font-family: tahoma;
		}
		img {
			max-width: 100%;
		}
		.wrap {
		}
		.img {
			border-radius: 50%;
			width: 100px;
		}
		.row1, .row2, .row6, .row7, .wrap1 {
			background-color: #a1a1a1;
		}
		.row3, .row4, .row5, .row8, .wrap2 {
			background-color: #ccc;
		}
                       .row1, .row7 {
			width: 80%;
			margin: 0 auto;
			display: grid;
			grid-template-columns: auto auto;
			grid-gap: 20px;
		}
		.row4, .row5 {
			width: 80%;
			margin: 0 auto;
			display: grid;
			grid-template-columns: auto auto auto;
			grid-gap: 20px;
			padding-bottom: 30px;
		}
		.bgwhite {
			background-color: #fff;
		}
		.bgblack {
			background-color: #000;
			color: #fff;
		}
		.alignright {
			text-align: right;
		}
		.aligncenter {
			text-align: center;
		}
		.row1, .pad20 {
			padding: 20px;
		}
		.row2 a {
			background-color: #000;
			color: #fff;
			padding: 10px 15px;
			text-decoration: none;
		}

@media only screen and (max-width:576px) {
			.row1, .row7, .row4, .row5 {
				grid-template-columns: auto;
			}
			.row1 div, .row7 div {
				text-align: center;
			}
			.row7 div ul {
				text-align: left;
			}
		}
		</style>
	</head>
<body>
		<div class="wrap1">
			<div class="row1">
				<div><img src="ME.2.jpeg" class="img"></div>
				<div class="alignright pad20">
					<h4>Sahil Saify</h4>
					<p>Web Developer<br>
					CSE Student</p>
				</div>
			</div>
		</div>
		<div class="wrap">
			<div class="row2 aligncenter pad20">
				<a href="">Projects</a><a href="">About</a><a href="">Contact</a>
			</div>
		</div>
		<div class="wrap">
			<div class="row3 aligncenter pad20">
				<h2>Projects/Certifications</h2>
			</div>
		</div>
<div class="wrap2">
			<div class="row4">
				<div>
					<img src="Amazon.jpg">
					<p>AMAZON WEB SERVICES</p>
					<p>6 Weeks Complete project </p>
				</div>
				<div>
					<img src="AIForeveryone.jpg">
					<p>ARTIFICIAL INTELLIGENCE</p>
					<p>Project Description- Full course Machine learning and AI.</p>
				</div>
				<div>
					<img src="WebIntern.jpg">
					<p>WEB DEVELOPMENT</p>
					<p>Project Description- Full stack webpage dovelopment.</p>
				</div>
			</div>
		</div>

<div class="wrap2">
			<div class="row5">
				<div>
					<img src="FirstInPaint.jpg">
					<p>FIRST PRIZE IN PAINTING</p>
					<p>Project Description - Painting competition by NSS.</p>
				</div>
				<div>
					<img src="CertificateofExcellence.jpg">
					<p>QUIZ COMPETITION</p>
					<p>Project Description- Full marks in NSS quiz</p>
				</div>
				<div>
					<img src="ParticipationQuizomania.jpg">
					<p>Participation In NSS Quiz</p>
					<p>Nss quiz participation on foundation day</p>
				</div>
			</div>
		</div>
		<div class="wrap">
			<div class="row6 aligncenter pad20">
				<h2>About Me</h2>
			</div>
		</div>
<div class="wrap1">
			<div class="row7">
				<div class="bgwhite pad20">
					<h4 class="aligncenter">Personal Details</h4>
					<ul>
						<li>Sahil Saify</li>
						<li>DOB: 30-10-01</li>
						<li>PHONE:_________</li>
						<li>Status: Umarried</li>
						<li>Under-graduate</li>
					</ul>
				</div>
				<div class="bgblack pad20">
					<h4 class="aligncenter">Education/Skillset</h4>
					<ul>
						<li>B.Ttech</li>
						<li>HTML</li>
						<li>CSS</li>
						<li>PHP</li>
						<li>Developer</li>
					</ul>
				</div>
			</div>
		</div>
		<div class="wrap">
			<div class="row8 aligncenter pad20">&copy; Copyright 2020.</div>
		</div>
	</body>
</html>


