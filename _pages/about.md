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
    width: 100%;
    margin-bottom: 15px;
  }
  .pub-image img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 8px;
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
        <img src="images/paper10_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Seeing like a Cephalopod: Colour Vision with a Monochrome Event Camera</h3>
        <p><strong>Sami Arja</strong>, Nimrod Kruger, Alexandre Marcireau, Nicholas Owen Ralph, Saeed Afshar and Gregory Cohen</p>
        <p class="pub-venue">Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2025 (Event-based Workshop)</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://link-to-paper.com" target="_blank">Paper</a>
        <a class="pub-btn" href="https://github.com/samiarja/OctoEye" target="_blank">Code</a>
        <a class="pub-btn" href="https://samiarja.github.io/neuromorphic_octopus_eye/" target="_blank">Project Page</a>
      </div>
    </div>
    
    <!-- Publication Item 2 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper9_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Performance metrics for neuromorphic imaging</h3>
        <p>Nimrod Kruger, <strong>Sami Arja</strong>, Evie Andrew, Travis Monk, André van Schaik</p>
        <p class="pub-venue">Quantum Sensing and Nano Electronics and Photonics XXI</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13376/133760D/Performance-metrics-for-neuromorphic-imaging/10.1117/12.3041873.short" target="_blank">Paper</a>
      </div>
    </div>
    
    <!-- Publication Item 3 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper8_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Noise Filtering Benchmark for Neuromorphic Satellites Observations</h3>
        <p><strong>Sami Arja</strong>, Alexandre Marcireau, Nicholas Owen Ralph, Saeed Afshar, Gregory Cohen</p>
        <p class="pub-venue">arXiv, 2024</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://arxiv.org/pdf/2411.11233" target="_blank">Paper</a>
        <a class="pub-btn" href="https://github.com/samiarja/dvs_sparse_filter" target="_blank">Code</a>
      </div>
    </div>
    
    <!-- Publication Item 4 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper7_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Active Neuromorphic Space Imaging and Focusing using Liquid Lenses</h3>
        <p>Nicholas Owen Ralph, Darren Maybour, Alexandre Marcireau, Nik Dennler, <strong>Sami Arja</strong>, Nimrod Kruger, Gregory Cohen</p>
        <p class="pub-venue">arXiv, 2024</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://d197for5662m48.cloudfront.net/documents/publicationstatus/231906/preprint_pdf/f181a923c5df588405a8cbf9e526ae9b.pdf" target="_blank">Paper</a>
      </div>
    </div>


    <!-- Publication Item 5 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper6_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Motion Segmentation for Neuromorphic Aerial Surveillance</h3>
        <p><strong>Sami Arja</strong>, Alexandre Marcireau, Saeed Afshar, Bharath Ramesh, Gregory Cohen</p>
        <p class="pub-venue">arXiv, 2024</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://arxiv.org/pdf/2405.15209" target="_blank">Paper</a>
        <a class="pub-btn" href="https://github.com/samiarja/ev_deep_motion_segmentation" target="_blank">Code</a>
        <a class="pub-btn" href="https://samiarja.github.io/evairborne/" target="_blank">Project Page</a>
      </div>
    </div>

    <!-- Publication Item 6 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper5_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Density invariant contrast maximization for neuromorphic Earth observations</h3>
        <p><strong>Sami Arja</strong>, Alexandre Marcireau, Richard L Balthazor, Matthew G McHarg, Saeed Afshar, Gregory Cohen</p>
        <p class="pub-venue">Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2023 (Event-based Workshop)</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://openaccess.thecvf.com/content/CVPR2023W/EventVision/papers/Arja_Density_Invariant_Contrast_Maximization_for_Neuromorphic_Earth_Observations_CVPRW_2023_paper.pdf" target="_blank">Paper</a>
        <a class="pub-btn" href="https://github.com/neuromorphicsystems/event_warping" target="_blank">Code</a>
        <a class="pub-btn" href="https://samiarja.github.io/earthobservation/" target="_blank">Project Page</a>
      </div>
    </div>

    <!-- Publication Item 7 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper4_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Neuromorphic engineering needs closed-loop benchmarks</h3>
        <p>Moritz B Milde, Saeed Afshar, Ying Xu, Alexandre Marcireau, Damien Joubert, Bharath Ramesh, Yeshwanth Bethi, Nicholas O Ralph, <strong>Sami Arja</strong>, Nik Dennler, André van Schaik, Gregory Cohen</p>
        <p class="pub-venue">Frontiers Neuroscience, 2022</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2022.813555/full" target="_blank">Paper</a>
      </div>
    </div>

    <!-- Publication Item 8 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper3_thumbnail.jpg" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Neuromorphic Perception for Greenhouse Technology Using Event-based Sensors</h3>
        <p><strong>Sami Arja</strong></p>
        <p class="pub-venue">Master Thesis, 2021</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://core.ac.uk/download/pdf/544084456.pdf" target="_blank">Paper</a>
      </div>
    </div>

    <!-- Publication Item 9 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper2_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Characterisation of Morphic Sensors for Body Volume and Shape Applications</h3>
        <p><strong>Sami Arja</strong>, Titus Jayarathna, Ganesh Naik, Paul Breen, Gaetano Gargiulo</p>
        <p class="pub-venue">Sensors 2020</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://www.mdpi.com/1424-8220/20/1/90" target="_blank">Paper</a>
      </div>
    </div>

    <!-- Publication Item 10 -->
    <div class="publication-item">
      <div class="pub-image">
        <img src="images/paper1_thumbnail.png" alt="Thumbnail">
      </div>
      <div class="pub-details">
        <h3>Characterization of Coated Piezo-resistive Fabric for Respiration Sensing</h3>
        <p><strong>Sami Arja</strong>, Titus Jayarathna, Felipe Ulloa, Gaetano Gargiulo, Paul Breen</p>
        <p class="pub-venue">International Conference on Electrical Engineering Research & Practice (ICEERP), 2019</p>
      </div>
      <div class="pub-buttons">
        <a class="pub-btn" href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8956989" target="_blank">Paper</a>
      </div>
    </div>
    
  </div>
</div>


  
