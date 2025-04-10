---
permalink: /
title: "Sami Arja"
excerpt: "About me"
author_profile: true
# redirect_from:
#  - /about/
#  - /about.html
---

I am a PhD candidate at the [International Centre for Neuromorphic Systems (ICNS)](https://www.westernsydney.edu.au/icns) at Western Sydney University, where I am mainly advised by A/Prof. [Gregory Cohen](http://greg-cohen.com/), Dr. [Saeed Afshar](https://scholar.google.com.au/citations?user=a8FPrPwAAAAJ&hl=en), and Dr. [Alexander Marcireau](https://scholar.google.com/citations?user=43KBWgoAAAAJ&hl=en). My research focuses on event-based motion estimation for space-related applications.

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

<style>
  /* Global Styles */
  body {
    font-family: 'Helvetica Neue', Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
  }
  .container {
    max-width: 800px;
    margin: 30px auto;
    padding: 30px;
    background-color: transparent; /* matching overall background */
  }
  h1, h2, h3 {
    color: #333;
    margin: 0 0 15px;
  }

  /* Publications Section */
  .publications {
    margin-bottom: 40px;
  }
  .publications h2 {
    font-size: 28px;
    color: #333;
    border-bottom: 2px solid #ccc;
    padding-bottom: 5px;
    margin-bottom: 20px;
    text-align: center;
  }
  .publication-item {
    display: flex;
    flex-direction: column;
    background-color: #fff;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .publication-item:hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  }
  .pub-image {
    flex: 0 0 500px;        /* Reduced width */
    margin-right: 20px;
    text-align: center;      /* Ensure content is centered */
  }
  .pub-image img {
    width: 500px;           /* Reduced width */
    height: auto;
    display: inline-block; /* Allows margin auto if needed */
    border-radius: 4px;
  }
  .pub-details {
    text-align: center;
  }
  .pub-details h3 {
    font-size: 22px;
    margin-bottom: 8px;
  }
  .pub-details p {
    margin: 4px 0;
    color: #555;
  }
  .pub-venue {
    font-style: italic;
    color: #777;
    margin-top: 5px;
    margin-bottom: 10px;
  }
  /* Publication Buttons */
  .pub-buttons {
    margin-top: 15px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
  }
  .pub-btn {
    display: inline-block;
    padding: 10px 15px;
    border: 1px solid #ccc;
    border-radius: 4px;
    background: linear-gradient(135deg, #6a11cb, #2575fc);
    color: #fff;
    text-decoration: none;
    font-size: 16px;
    transition: background 0.3s ease;
  }
  .pub-btn:hover {
    background: linear-gradient(135deg, #2575fc, #6a11cb);
  }

  /* Education Section */
  .education {
    margin-bottom: 40px;
  }
  .education h1 {
    font-size: 24px;
    font-weight: bold;
    color: #333;
    border-bottom: 2px solid #ccc;
    padding-bottom: 5px;
    margin-bottom: 20px;
    text-align: center;
  }
  .education ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  .education li {
    margin-bottom: 10px;
    font-size: 18px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .education li sup {
    margin-left: 10px;
    font-size: 14px;
    color: #666;
  }
  .education li .fa-graduation-cap,
  .education li .fa-spinner {
    margin-right: 10px;
    font-size: 18px;
    color: #333;
  }
  .education li .fa-spinner {
    animation: spin 2s linear infinite;
  }
  @keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }

  /* Footer Styles */
  .footer {
    margin-top: 30px;
    font-size: 14px;
    color: #666;
    text-align: center;
  }
  .footer a {
    color: #666;
    text-decoration: none;
    transition: color 0.2s ease-in-out;
  }
  .footer a:hover {
    color: #333;
  }
</style>


<div class="container">
  <!-- Education Section -->
  <div class="education">
    <h1>Education - Western Sydney University</h1>
    <ul>
      <li><i class="fas fa-spinner"></i> PhD - Neuromorphic Engineering, 2022 - 2025</li>
      <li><i class="fas fa-graduation-cap"></i> Master - Neuromorphic Engineering, 2019 - 2021</li>
      <li><i class="fas fa-graduation-cap"></i> Bachelor (Honours) - Robotics and Mechatronics Engineering, 2015 - 2019</li>
    </ul>
  </div>



<div class="container">
  <!-- Publications Section -->
  <div class="publications">
    <h2>Publications List</h2>
    
    <!-- Publication Item 1 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 1</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>
    
    <!-- Publication Item 2 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 2</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>
    
    <!-- Publication Item 3 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 3</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>
    
    <!-- Publication Item 4 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 4</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>


    <!-- Publication Item 5 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 5</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>

    <!-- Publication Item 6 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 6</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>

    <!-- Publication Item 7 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 7</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>

    <!-- Publication Item 8 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 8</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>

    <!-- Publication Item 9 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="static/images/thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Paper Title 9</h3>
        <p>Author1, Author2, Author3</p>
        <p class="pub-venue">Conference Name, Year</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://link-to-code.com" target="_blank">Code</a>
        <a class="pub-btn" href="https://link-to-project.com" target="_blank">Project Page</a>
      </div>
    </div>

    <!-- Publication Item 10 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper1_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Characterization of Coated Piezo-resistive Fabric for Respiration Sensing</h3>
        <p>Sami El Arja, Titus Jayarathna, Felipe Ulloa, Gaetano Gargiulo, Paul Breen</p>
        <p class="pub-venue">2019 International Conference on Electrical Engineering Research & Practice (ICEERP)</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8956989" target="_blank">Paper</a>
      </div>
    </div>
    
  </div>
</div>


  
