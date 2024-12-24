---
layout: default
title: Projects
permalink: /projects/
---

<!---DOCTYPE html --->
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap Carousel & Project Grid</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <!-- JQuery -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <!-- Bootstrap JS -->
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <style>
    .project-image {
      width: 500px;
      height: 500px;
      object-fit: cover; /* Ensures images fit well without distortion */
    }
  </style>
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
        <img src="/img/projects/KOSPI.jpg" class="project-image" alt="KOSPI Project">
        <div class="carousel-caption">
          <h3>Assessing Time-Series Relationships Between South Korean KOSPI and U.S. NASDAQ</h3>
          <p>A time series project hoping to predict future NASDAQ prices using limited data on past NASDAQ and KOSPI prices.</p>
        </div>
      </div>

      <!-- Slide 2 -->
  <div class="item">
        <img src="/img/projects/income.jpg" class="project-image" alt="Project 2">
        <div class="carousel-caption">
          <h3>Deciphering Earnings</h3>
          <p>
           A collaborative project utilizing binomial classification techniques to predict income levels above $50K. 
          </p>
        </div>
      </div>

      <!-- Slide 3 -->
   <div class="item">
        <img src="img/portfolio/project3.jpg" class="project-image" alt="Project 3">
        <div class="carousel-caption">
          <h3>Project 3: E-commerce Platform</h3>
          <p>This project showcases an e-commerce website built with React and Node.js. It supports product browsing, shopping carts, and checkout functionality.</p>
        </div>
      </div>
    </div>

    <!-- Left and right controls --
  <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>

  <!-- Grid of Projects Below the Carousel -->
  <h2>All Projects</h2>
  <div class="row">
    <!-- Project 1 -->
    <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="img/portfolio/project4.jpg" class="project-image" alt="Project 4">
        <div class="caption">
          <h3>Project 4: Mobile App</h3>
          <p>Developed a mobile app for tracking personal fitness goals. The app includes data visualization for progress tracking and goal setting.</p>
        </div>
      </div>
    </div>

    <!-- Project 2 -->
  <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="img/portfolio/project5.jpg" class="project-image" alt="Project 5">
        <div class="caption">
          <h3>Project 5: Machine Learning</h3>
          <p>A machine learning project using TensorFlow to predict stock prices based on historical data. Implemented regression models and evaluated performance metrics.</p>
        </div>
      </div>
    </div>

    <!-- Project 3 -->
  <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="img/portfolio/project6.jpg" class="project-image" alt="Project 6">
        <div class="caption">
          <h3>Project 6: Blogging Platform</h3>
          <p>Built a blogging platform where users can post articles, comment, and like posts. Utilized Django for the back-end and Bootstrap for the front-end.</p>
        </div>
      </div>
    </div>

    <!-- Add more projects here as needed -->
  </div>
</div>

</body>
</html>
