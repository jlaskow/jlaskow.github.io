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
    /* Styling for uniform image sizes */
    .carousel-inner img {
      width: 50%; /* Adjust width as needed */
      height: auto;
      float: left; /* Align image to the left */
    }

   .carousel-caption {
      position: absolute;
      right: 15%;
      top: 50%;
      transform: translateY(-50%);
      color: black; /* Title and description in black */
      text-align: left;
      width: 40%;
    }
    
  .carousel-caption h3 {
      font-weight: bold;
    }

  .carousel {
      position: relative;
    }
  </style>
</head>
<body>
<div class="container">
  <!-- Carousel -->
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Wrapper for slides -->
    <div class="carousel-inner">
      <!-- Slide 1 -->
      <div class="item active">
        <img src="/img/projects/KOSPI.jpg" alt="KOSPI Project">
        <div class="carousel-caption">
          <h3>NASDAQ Predictions</h3>
          <p>A time series project hoping to predict future NASDAQ prices using limited data on past NASDAQ and KOSPI prices.</p>
        </div>
      </div>
      <!-- Slide 2 -->
      <div class="item">
        <img src="/img/projects/income.jpg" alt="Project 2">
        <div class="carousel-caption">
          <h3>Deciphering Earnings</h3>
          <p>A collaborative project utilizing binomial classification techniques to predict income levels above $50K.</p>
        </div>
      </div>
      <!-- Slide 3 -->
      <div class="item">
        <img src="/img/projects/ensemble.jpg" alt="Project 3">
        <div class="carousel-caption">
          <h3>Advanced Predictive Modeling Techniques</h3>
          <p>An independent project seeking analytical tools and stacked ensembling techniques to predict patient medical expenses.</p>
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















  <!-- Grid of Projects Below the Carousel -->
  <h2>All Projects</h2>
  <div class="row">
    <!-- Project 1 -->
    <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <div class="caption">
          <h3>NASDAQ Predictions</h3>
          <p>A time series project hoping to predict future NASDAQ prices using limited data on past NASDAQ and KOSPI prices.</p>
        </div>
      </div>
    </div>

    <!-- Project 2 -->

  <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <div class="caption">
          <h3>Deciphering Earnings</h3>
          <p>A collaborative project utilizing binomial classification techniques to predict income levels above $50K.</p>
        </div>
      </div>
    </div>

    <!-- Project 3 -->
  
  <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <div class="caption">
          <h3>Advanced Predictive Modeling Techniques</h3>
          <p>An independent project seeking to use a multitude of analytical tools and stacked ensembling techniques to build reliable predictions of patient medical expenses.</p>
        </div>
      </div>
    </div>



    
    <!-- Project 4 -->
  
  <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <div class="caption">
          <h3>Beers and Breweries</h3>
          <p>Exploratory analytics for Budweiser sales data, focusing on marketing insights and opportunities for supply chain optimization.</p>
        </div>
      </div>
    </div>


    
    <!-- Project 5 -->
  
  <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <div class="caption">
          <h3>Dragon's Hoard</h3>
          <p>Cloud-based data pipeline of a low-cost, user-friendly CRM for wholesale distributors to track sale and contract leads.</p>
        </div>
      </div>
    </div>


    
    <!-- Project 6 -->
  
  <div class="col-lg-4 col-md-6">
      <div class="thumbnail">
        <div class="caption">
          <h3>Employee Demographics for FritoLay</h3>
          <p>Application of KNN Clustering and Naive Bayes to predict employee attrition, and the use of multiple linear regression to predict employee salary.</p>
        </div>
      </div>
    </div>




    





  </div>
</div>

</body>
</html>
