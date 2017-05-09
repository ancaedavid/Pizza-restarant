# Pizza-restarant
<!doctype html>
<html lang="en">
<head>

<title> GOLDEN HEARTH </title>

		<meta charset="UTF-8">
		<meta>


<style>

header { background-color:black;
	color: gold;
	text-align:center;
	padding:2px;
                  }

.fixed-header  {
	float: none;
	}

header a {
	text-decoration: none
	}


nav {	height:100%;  <!--100% full-height-->
	width:0;
	top:0;
	left:0;
	background-color:black;
	padding:6px;
	z-index:1;   <!--stay on top-->
	overflow-x:hidden;   <!--disable horizontal scroll-->
	position:fixed;   <!--stay in place-->
	padding-top:80px;
	transition:0.5s;
	}

nav ul { 
	list-style-type:none;
	float:left;
	color:gold;
	}

nav li {
	padding:7px;
	}

nav a { 
	text-decoration: none;
	color:gold;
	}
nav a:hover, offcanvas a:focus {
	text-decoration:underline;
	}

nav.closebtn {
	position:absolute;
	top:0;
	right:25px;
	font-size:25px;
	margin-left50px;
	}

@media screen and (max-height: 450px) {
  nav {padding-top: 15px;}
  nav a {font-size: 18px;}





.topnav {
	overflow:hidden;
	background-color:black;


	}

.topnav a {
	text-decoration:none;
	color:gold;
	padding:40px;

	}

.topnav a:hover{
	text-decoration:underline;

	}


footer {
	background-color:black;
	color:gold;
	text-align:center;
	}


</style>

</head>



<body>




<header>

<h1 > &#9617;&#9617;&#9617;&#9617;&#9617; GOLDEN HEARTH &#9617;&#9617;&#9617;&#9617;&#9617;</h1>


<div class="topnav">
	<a href="#" >YOUR ORDER</a>
	<a href="#">OFFERs</a>
	<a href=""#>SIGN UP</a>
	<a href="#">HELP & CONTACT</a>
</div>


</header>





<nav id="MySidenav">

<ul >

	<li> <a href="#">PIZZA</a></>
	<li><a href="#">CREATE YOUR PIZZA</a></li>
	<li><a href="#">PASTE</a></li>
	<li><a href="#">SALADS</a></li>
</ul>

</nav>



<div id="main">
	



</div>





<footer>
	Copyright &copy; Elena Rusu
</footer>

</body>

</html>
