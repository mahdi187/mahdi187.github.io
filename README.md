<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<title>
Home
</title>
<link rel="stylesheet" type="text/css" href="style	.css">



</head>
<body>
<div class="wrap">
		<div class="header">
		  <img src="logo.png" width="200px" alt="logo">
			<h1>Savannah Restaurant</h1>
			
			<div id="nav">
			
			<nav>
	
<ul>
<li><a href="index.html">home</a></li>
<li><a href="information.html">information</a></li>
<li><a href="contact.html">contact</a></li>
<li><a href="about.html">about</a></li>
</ul>
  
  
</nav>
		</div>
		</div>
		

	<div class="section">
		
			
			<h2><i>Welcome to Savannah Restaurant</i></h2>
<br>

<h3>WE WELCOME YOU TO SAVANNAH RESTAURANT:</h3p>
<p>WE ARE A FUN LOVING, AFRICAN RESTAURANT LOCATED IN THE PRESTIGIOUS AREA OF PARNELL ST, DUBLIN 1. WITH OUR MORDERN
 INTERIOR AND LARGE MENU, WE BRING YOU AN AUTHENTIC, TASTE OF AFRICA.</p><br>


<p>Savannah cuisine, like most African cuisine is known for its richness, deep flavour and variety. Various spices, herbs and flavourings 
are used together with palm oil or groundnut oil to create deeply flavoured stews and soups usually made from hot chili peppers.
 African feasts are incomplete without an array of traditional dishes. At Savannah Restaurant, we prepare our meals to contemporary 
standards while maintaining that unique traditional African food...</p></p>
<br>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="Images/images 2.png" style="width:100%">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="Images/image 3.png" style="width:100%">
  <div class="text">Caption Three</div>
</div>

<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 3000); // Change image every 3 seconds
}
</script>



			




<h3>Business Hours:</h3>
 
<table>
  <tr>
    <th>Mon</th>
    <th>Tue</th>
    <th>Wed</th>
      <th>Thu</th>
    <th>Fri</th>
    <th>Sat</th>
    <th>Sun</th>
  </tr>
  <tr>
    <td>8:00 a.m - 10 p.m</td>
     <td>8:00 a.m - 10 p.m</td>
        <td>8:00 a.m - 10 p.m</td>
        <td>8:00 a.m - 10 p.m</td>
        <td>8:00 a.m - 10 p.m</td>
        <td>8:00 a.m - 10 p.m</td>
    <td>8:00 a.m - 10 p.m</td>
  </tr>
  
 </table>
 <p><i>Holidays hours</i></p>
 <table>
  <tr>
    <th>Mon</th>
    <th>Tue</th>
    <th>Wed</th>
      <th>Thu</th>
    <th>Fri</th>
    <th>Sat</th>
    <th>Sun</th>
  </tr>
  <tr>
    <td>8:00 a.m - 03 p.m</td>
     <td>8:00 a.m - 03 p.m</td>
        <td>8:00 a.m - 03 p.m</td>
        <td>8:00 a.m - 03 p.m</td>
        <td>8:00 a.m - 03 p.m</td>
        <td>8:00 a.m - 02 p.m</td>
    <td>8:00 a.m - 01 p.m</td>
  </tr>
  
 </table>

		</div>

	
	<div class="footer">
&copy;copyright Savannah restaurant Dublin 2021
	</div>
	</div>
</body>
</html>
