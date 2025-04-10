---
layout: landing
theme: Home
title: UK-Space-LABS
logo: ![UK-Space-LABS logo](images/Space_Logo_col_dEC_14.jpg)

subtitle: Welcome - The UK Space Life and Biomedical Sciences Association

--- 

<!-- under_construction parameter sat to 'true' in the _config.yaml -->
{% if site.under_construction %}
<div class="maintenance-page">
  <!--!DOCTYPE html-->
  <html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Houston, We Have Maintenance</title>
    <style>
      body {
        margin: 0;
        background: #0b0c10;
        color: #fff;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        overflow: hidden;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-image: url('images/earth_from_moon.png');
      }
      .container {
        text-align: center;
        padding: 2rem;
      }
      .astronaut {
        font-size: 6rem;
        animation: float 3s ease-in-out infinite;
      }
      @keyframes float {
        0%, 100% { transform: translateY(0); }
        50% { transform: translateY(-20px); }
      }
      .astronaut img {
        width: 150px;
        animation: float 3s ease-in-out infinite;
        filter: drop-shadow(0 0 5px #0ff);
      }
      h1 {
        font-size: 2.5rem;
        margin-top: 1rem;
      }
      p {
        font-size: 1.2rem;
        color: #aaa;
      }
      .comet {
        position: absolute;
        top: 20%;
        left: -200px;
        width: 100px;
        height: 4px;
        background: linear-gradient(90deg, #0ff, transparent);
        animation: comet 6s linear infinite;
      }
      @keyframes comet {
        0% { left: -200px; top: 20%; }
        100% { left: 120%; top: 10%; }
      }
    </style>
  </head>
  <body>
    <div class="comet"></div>
    <div class="container">
      <div class="astronaut">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Tardigrade_microanimal.png" alt="Space Tardigrade" />
      </div>
      <h1>Houston, We Have Maintenance...</h1>
      <p>Our spaceship is undergoing a quick tune-up. We'll be launching again shortly!</p>
      <p>In the meantime, don't forget to hydrate... even in zero gravity.</p>
    </div>
  </body>
  </html>
</div>
{% else %}
<!-- Your regular content here -->

# Overview

The UK Space Life and Biomedical Sciences Association aids and supports UK communities interested in the fields of space life and biomedical sciences.

{% endif %}

