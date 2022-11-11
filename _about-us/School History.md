---
title: School History
permalink: /history/
description: ""
---
```
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 7</div>
  <img src="C:\Users\s8510979j\Desktop\sample_pix\number1.png" style="width:100%">
  <div class="text">This is Image No. 1</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 7</div>
  <img src="C:\Users\s8510979j\Desktop\sample_pix\number2.png" style="width:100%">
  <div class="text">This is Image No. 2</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 7</div>
  <img src="C:\Users\s8510979j\Desktop\sample_pix\number3.png" style="width:100%">
  <div class="text">This is Image No. 3</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 7</div>
  <img src="C:\Users\s8510979j\Desktop\sample_pix\number4.png" style="width:100%">
  <div class="text">This is Image No. 4</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 7</div>
  <img src="C:\Users\s8510979j\Desktop\sample_pix\number5.png" style="width:100%">
  <div class="text">This is Image No. 5</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 7</div>
  <img src="C:\Users\s8510979j\Desktop\sample_pix\number6.png" style="width:100%">
  <div class="text">This is Image No. 6</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">7 / 7</div>
  <img src="C:\Users\s8510979j\Desktop\sample_pix\number7.png" style="width:100%">
  <div class="text">This is Image No. 7</div>
</div>

<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
  <span class="dot" onclick="currentSlide(6)"></span>
  <span class="dot" onclick="currentSlide(7)"></span>
</div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
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

</body>
</html> 
```

### School History

Serangoon Secondary School started out as Serangoon English School in 1928, housed in a two-storey building on Simon Road. It was then the only government co-educational school in Singapore, and it also served as a feeder school to Raffles Institution.

  

In 1937, three more standards were added; with this, the school provided education up to Standard Eight (equivalent of present-day Secondary Three). The boys and girls who successfully completed Standard Eight went on to Raffles Institution and Raffles Girls’ School respectively, where they would sit for the School Certificate of Examinations (equivalent to the O-Level examinations today). Serangoon English School remained a feeder school until the eve of the Japanese Occupation of Singapore.

  

During the Japanese Occupation, the school was known as the Japanese Higher Normal School. It was used to train government officials under the Japanese education system.

  

In 1949, the school became a full school, with its first School Certificate class offering education from Primary One to Cambridge School Certificate (O-Level equivalent). In 1957, the school officially became a secondary school for the Upper Serangoon district, after ceasing primary school classes that year. In 1965, the first pre-university classes were started and girls were admitted to these classes.

  

In 1967, Serangoon English School relocated to Lowland Road and was renamed as Serangoon Secondary School. In that year, the school badge was modified and the old school motto, ‘Play the Game’, was replaced with ‘Knowledge is Power’. The present school song was also introduced. In 1976, pre-university classes were discontinued. In 1989, the school motto was changed again to ‘Seek, Strive, Serve’.

  

To mark the new millennium, in 2001, the school moved to its present premises at 11 Upper Serangoon View and continues to provide a student-centric, values-driven education. In 2018, Serangoon Secondary celebrated its 90th anniversary.