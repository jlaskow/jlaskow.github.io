---
layout: default
title: Projects
permalink: /projects/
---





<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap Carousel Example</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <!-- JQuery -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <!-- Bootstrap JS -->
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>
<body>

<div class="container">
  <h2>Project Carousel</h2>  
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
  <div class="carousel-inner">
      <!-- Slide 1 -->
      <div class="item active">
        <img src="img/portfolio/project1.jpg" alt="Project 1" style="width:100%;">
        <div class="carousel-caption">
          <h3>Project 1: Web Development</h3>
          <p>This project involves creating a responsive website using HTML, CSS, and JavaScript. The site features a dynamic navigation menu and interactive elements.</p>
        </div>
      </div>

      <!-- Slide 2 -->
  <div class="item">
        <img src="img/portfolio/project2.jpg" alt="Project 2" style="width:100%;">
        <div class="carousel-caption">
          <h3>Project 2: Data Visualization</h3>
          <p>A data visualization project using D3.js to create interactive charts. The data includes information on sales trends over the past year.</p>
        </div>
      </div>
    
      <!-- Slide 3 -->
  <div class="item">
        <img src="img/portfolio/project3.jpg" alt="Project 3" style="width:100%;">
        <div class="carousel-caption">
          <h3>Project 3: E-commerce Platform</h3>
          <p>This project showcases an e-commerce website built with React and Node.js. It supports product browsing, shopping carts, and checkout functionality.</p>
        </div>
      </div>
    </div>

    <!-- Left and right controls -->
  
  <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

</body>
</html>
