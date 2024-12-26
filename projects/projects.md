---
layout: special
title: Projects
permalink: /projects/
---
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projects Grid</title>
  <style>
    .projects-container {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      padding: 20px;
    }
    .project-box {
      width: 200px;
      border: 1px solid #ccc;
      border-radius: 5px;
      overflow: hidden;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .project-box:hover {
      transform: scale(1.05);
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }
    .project-box img {
      width: 50px;
      height: 50px;
      object-fit: cover;
      margin: 10px auto;
      border-radius: 50%;
    }
    .project-box h3 {
      font-size: 16px;
      margin: 10px 0;
    }
    .project-box p {
      font-size: 14px;
      padding: 0 10px 10px;
      margin: 0;
      color: #666;
    }
  </style>
</head>
<body>
  <div class="projects-container">
    <!-- Project 1 -->
    <a href="https://example.com/nasdaq" target="_blank" class="project-box">
      <img src="/img/projects/KOSPI.jpg" alt="KOSPI Project">
      <h3>NASDAQ Predictions</h3>
      <p>Predict future NASDAQ prices using limited data.</p>
    </a>
    <!-- Project 2 -->
    <a href="https://example.com/income" target="_blank" class="project-box">
      <img src="/img/projects/income.jpg" alt="Income Project">
      <h3>Deciphering Earnings</h3>
      <p>Predict income levels above $50K with classification techniques.</p>
    </a>
    <!-- Project 3 -->
    <a href="https://example.com/ensemble" target="_blank" class="project-box">
      <img src="/img/projects/ensemble.jpg" alt="Ensemble Project">
      <h3>Predictive Modeling</h3>
      <p>Use stacked ensembling to predict medical expenses.</p>
    </a>
    <!-- Project 4 -->
    <a href="https://example.com/beer" target="_blank" class="project-box">
      <img src="/img/projects/beer.jpg" alt="Beers and Breweries">
      <h3>Beers and Breweries</h3>
      <p>Insights into Budweiser sales data.</p>
    </a>
    <!-- Project 5 -->
    <a href="https://example.com/dragon" target="_blank" class="project-box">
      <img src="/img/projects/dragon.jpg" alt="Dragon's Hoard">
      <h3>Dragon's Hoard</h3>
      <p>Cloud-based CRM for wholesale distributors.</p>
    </a>
    <!-- Project 6 -->
    <a href="https://example.com/fritolay" target="_blank" class="project-box">
      <img src="/img/projects/fritolay.jpg" alt="FritoLay Employee Demographics">
      <h3>FritoLay Demographics</h3>
      <p>Predict employee attrition and salary trends.</p>
    </a>
  </div>
</body>
</html>
