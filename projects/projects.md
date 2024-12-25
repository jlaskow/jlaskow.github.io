---
layout: default
title: Projects
permalink: /projects/
---

<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <!-- JQuery -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <!-- Bootstrap JS -->
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
 
  
<style>
    /* General Carousel Styling */
    .carousel-inner {
      height: 400px; /* Set a consistent height for the carousel */
    }

  .carousel-item-container {
      display: flex;
      height: 100%;
      align-items: center; /* Align items vertically */
      justify-content: space-between; /* Separate the image and caption */
    }
    .carousel-item-container img {
      width: 48%; /* Slightly reduced width to account for spacing */
      height: 100%;
      object-fit: cover; /* Maintain aspect ratio */
    }
    .carousel-item-container .carousel-caption {
      width: 48%;
      padding: 20px;
      background-color: #f8f9fa;
      color: black;
      display: flex;
      flex-direction: column;
      justify-content: center; /* Center text vertically */
    }
    .carousel-caption h3 {
      font-weight: bold;
      margin-bottom: 10px;
    }

    /* Styling for "All Projects" section */
  .thumbnail img {
      width: 100%; /* Make images responsive */
      height: 200px; /* Consistent height for thumbnails */
      object-fit: cover;
    }
    .thumbnail {
      text-align: right;
    }
  </style>

</head>
<body>
<div class="container">
  <!-- Carousel -->
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <div class="carousel-inner">
      <!-- Slide 1 -->
      <div class="item active">
        <div class="carousel-item-container">
          <img src="/img/projects/KOSPI.jpg" alt="KOSPI Project">
          <div class="carousel-caption">
            <h3>NASDAQ Predictions</h3>
            <p>A time series project hoping to predict future NASDAQ prices using limited data on past NASDAQ and KOSPI prices.</p>
          </div>
        </div>
      </div>
      <!-- Slide 2 -->
      <div class="item">
        <div class="carousel-item-container">
          <img src="/img/projects/income.jpg" alt="Income Project">
          <div class="carousel-caption">
            <h3>Deciphering Earnings</h3>
            <p>A collaborative project utilizing binomial classification techniques to predict income levels above $50K.</p>
          </div>
        </div>
      </div>
      <!-- Slide 3 -->
      <div class="item">
        <div class="carousel-item-container">
          <img src="/img/projects/ensemble.jpg" alt="Ensemble Project">
          <div class="carousel-caption">
            <h3>Advanced Predictive Modeling Techniques</h3>
            <p>An independent project seeking analytical tools and stacked ensembling techniques to predict patient medical expenses.</p>
          </div>
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

  <!-- Grid of Projects Below the Carousel -->
  <h2>All Projects</h2>
  <div class="row">
    <!-- Project 1 -->
    <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="/img/projects/KOSPI.jpg" alt="KOSPI Project">
        <div class="caption">
          <h3>NASDAQ Predictions</h3>
          <p>A time series project hoping to predict future NASDAQ prices using limited data on past NASDAQ and KOSPI prices.</p>
        </div>
      </div>
    </div>
    <!-- Project 2 -->
    <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="/img/projects/income.jpg" alt="Project 2">
        <div class="caption">
          <h3>Deciphering Earnings</h3>
          <p>A collaborative project utilizing binomial classification techniques to predict income levels above $50K.</p>
        </div>
      </div>
    </div>
    <!-- Project 3 -->
    <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="/img/projects/ensemble.jpg" alt="Project 3">
        <div class="caption">
          <h3>Predictive Modeling Techniques</h3>
          <p>Analytical tools and stacked ensembling techniques to predict patient medical expenses.</p>
        </div>
      </div>
    </div>
    <!-- Project 4 -->
    <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="/img/projects/beer.jpg" alt="Project 4">
        <div class="caption">
          <h3>Beers and Breweries</h3>
          <p>Exploratory analytics for Budweiser sales data, focusing on marketing insights and supply chain optimization.</p>
        </div>
      </div>
    </div>
    <!-- Project 5 -->
    <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="/img/projects/dragon.jpg" alt="Project 5">
        <div class="caption">
          <h3>Dragon's Hoard</h3>
          <p>Cloud-based data pipeline for a user-friendly CRM to track sales and contract leads for wholesale distributors.</p>
        </div>
      </div>
    </div>
    <!-- Project 6 -->
    <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <img src="/img/projects/fritolay.jpg" alt="Project 6">
        <div class="caption">
          <h3>Employee Demographics for FritoLay</h3>
          <p>Application of KNN Clustering and Naive Bayes to predict employee attrition, along with salary predictions.</p>
        </div>
      </div>
    </div>
  </div>
</div>
</body>
</html>
