---
layout: archive
# title: "Publications"
permalink: /publications/
author_profile: true
---


<style>
  .button-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-bottom: 20px;
  }
  .button {
    background-color: #cccccc;
    border: none;
    color: white;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 25px;
    margin: 0;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
    box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.8);
  }
  .button:hover {
    background-color: #999999;
  }
  .button:active {
    box-shadow: inset 0px 1px 5px rgba(0, 0, 0, 0.2);
  }
  .button a {
    color: black;
    text-decoration: none;
  }
</style>

<script>
  function copyDOI5() {
    var doiLink = "arXiv:2304.14125";
    copyToClipboard(doiLink);
  }
  function copyCitation5() {
    fetch('dcmax.bib')
      .then(response => response.text())
      .then(text => {
        copyToClipboard(text);
      })
      .catch(error => console.log(error));
  }
  function copyToClipboard(text) {
    var textarea = document.createElement("textarea");
    textarea.value = text;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand("copy");
    document.body.removeChild(textarea);
    alert("Copied to clipboard: " + text);
  }
</script>


<script>
  function copyDOI6() {
    var doiLink = "arXiv:2405.15209";
    copyToClipboard(doiLink);
  }
  function copyCitation6() {
    fetch('motionseg.bib')
      .then(response => response.text())
      .then(text => {
        copyToClipboard(text);
      })
      .catch(error => console.log(error));
  }
  function copyToClipboard(text) {
    var textarea = document.createElement("textarea");
    textarea.value = text;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand("copy");
    document.body.removeChild(textarea);
    alert("Copied to clipboard: " + text);
  }
</script>

<div style="padding: 20px; border-radius: 10px;">
  <div style="display: flex; align-items: stretch;">
    <div style="flex-grow: 1; display: flex; align-items: center; justify-content: center; background-color: #333; padding: 20px; border-radius: 10px;">
      <h1 style="font-size: 28px; margin: 0; color: white;">Motion Segmentation for Neuromorphic Aerial Surveillance</h1>
    </div>
    <img src="./../images/motion_seg_architecture.png" style="width: 250px; height: auto; margin-left: 20px;">
  </div>
  
  <div style="display: flex; flex-direction: column;">
    <p>
      ArXiv, 2024
    </p>
    <p><strong>Sami Arja</strong>, Alexandre Marcireau, Saeed Afshar, Bharath Ramesh, Gregory Cohen</p>
  </div>
  
  <div class="button-container" style="padding-top: 20px;">
    <button class="button" onclick="copyCitation6()" style="color: black; font-size: 20px;">Cite</button>
    <button class="button" onclick="copyDOI6()" style="color: black; font-size: 20px;">DOI</button>
    <button class="button"><a href="https://arxiv.org/pdf/2405.15209.pdf" style="color: black; font-size: 20px;">PDF</a></button>
    <button class="button"><a href="https://samiarja.github.io/evairborne/" style="color: black; font-size: 20px;">Code</a></button>
  </div>
  <!-- </div> -->
</div>


<div style="padding: 20px; border-radius: 10px;">
  <div style="display: flex; align-items: stretch;">
    <div style="flex-grow: 1; display: flex; align-items: center; justify-content: center; background-color: #333; padding: 20px; border-radius: 10px;">
      <h1 style="font-size: 28px; margin: 0; color: white;">Density Invariant Contrast Maximization for Neuromorphic Earth Observations</h1>
    </div>
    <img src="./../images/cvpr_front_img.png" style="width: 250px; height: auto; margin-left: 20px;">
  </div>
  
  <div style="display: flex; flex-direction: column;">
    <p>
      IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2023
    </p>
    <p><strong>Sami Arja</strong>, Alexandre Marcireau, Richard L. Balthazor, Matthew G. McHarg, Saeed Afshar, Gregory Cohen</p>
  </div>
  
  <div class="button-container" style="padding-top: 20px;">
    <button class="button" onclick="copyCitation5()" style="color: black; font-size: 20px;">Cite</button>
    <button class="button" onclick="copyDOI5()" style="color: black; font-size: 20px;">DOI</button>
    <button class="button"><a href="https://arxiv.org/pdf/2304.14125.pdf" style="color: black; font-size: 20px;">PDF</a></button>
    <button class="button"><a href="https://github.com/neuromorphicsystems/event_warping" style="color: black; font-size: 20px;">Code</a></button>
  </div>
</div>


<hr style="border:1px solid black">

<div style="padding: 20px; border-radius: 10px;">
  <div style="display: flex; align-items: stretch;">
    <div style="flex-grow: 1; display: flex; align-items: center; justify-content: center; background-color: #333; padding: 20px; border-radius: 10px;">
      <h1 style="font-size: 28px; margin: 0; color: white;">Neuromorphic Engineering Needs Closed-Loop Benchmarks</h1>
    </div>
    <img src="./../images/benchmark.png" style="width: 250px; height: auto; margin-left: 20px;">
  </div>
  <div style="display: flex; flex-direction: column;">
    <p>
      Frontiers in Neuroscience, 2022
    </p>
    <p>Moritz B Milde, Saeed Afshar, Ying Xu, Alexandre Marcireau, Damien Joubert, Bharath Ramesh, Yeshwanth Bethi, Nicholas O Ralph, <strong>Sami Arja</strong>, Nik Dennler, André van Schaik, Gregory Cohen</p>
  </div>
  <div class="button-container" style="padding-top: 20px;">
    <button class="button" onclick="copyCitation4()" style="color: black; font-size: 20px;">Cite</button>
    <button class="button" onclick="copyDOI4()" style="color: black; font-size: 20px;">DOI</button>
    <button class="button"><a href="https://researchdirect.westernsydney.edu.au/islandora/object/uws:69020/datastream/PDF/view" style="color: black; font-size: 20px;">PDF</a></button>
  </div>
</div>


<style>
  .button-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-bottom: 20px;
  }
  .button {
    background-color: #cccccc;
    border: none;
    color: white;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 25px;
    margin: 0;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
    box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.8);
  }
  .button:hover {
    background-color: #999999;
  }
  .button:active {
    box-shadow: inset 0px 1px 5px rgba(0, 0, 0, 0.2);
  }
  .button a {
    color: black;
    text-decoration: none;
  }
</style>

<script>
  function copyDOI4() {
    var doiLink = "https://doi.org/10.3389/fnins.2022.813555";
    copyToClipboard(doiLink);
  }
  function copyCitation4() {
    fetch('benchamrk.bib')
      .then(response => response.text())
      .then(text => {
        copyToClipboard(text);
      })
      .catch(error => console.log(error));
  }
  function copyToClipboard(text) {
    var textarea = document.createElement("textarea");
    textarea.value = text;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand("copy");
    document.body.removeChild(textarea);
    alert("Copied to clipboard: " + text);
  }
</script>


<hr style="border:1px solid black">


<div style="padding: 20px; border-radius: 10px;">
  <div style="display: flex; align-items: stretch;">
    <div style="flex-grow: 1; display: flex; align-items: center; justify-content: center; background-color: #333; padding: 20px; border-radius: 10px;">
      <h1 style="font-size: 28px; margin: 0; color: white;">Neuromorphic Perception for Greenhouse Technology Using Event-based Sensors</h1>
    </div>
    <img src="./../images/secondnetworkarchitecturemodified.jpg" style="width: 250px; height: auto; margin-left: 20px;">
  </div>
  <div style="display: flex; flex-direction: column;">
    <p>
      MPhil Thesis, 2021
    </p>
    <p><strong>Sami Arja</strong></p>
  </div>
  <div class="button-container" style="padding-top: 20px;">
    <button class="button" onclick="copyCitation3()" style="color: black; font-size: 20px;">Cite</button>
    <button class="button" onclick="copyDOI3()" style="color: black; font-size: 20px;">DOI</button>
    <button class="button"><a href="https://researchdirect.westernsydney.edu.au/islandora/object/uws:67799/datastream/PDF/view" style="color: black; font-size: 20px;">PDF</a></button>
  </div>
</div>


<style>
  .button-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-bottom: 20px;
  }
  .button {
    background-color: #cccccc;
    border: none;
    color: white;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 25px;
    margin: 0;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
    box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.8);
  }
  .button:hover {
    background-color: #999999;
  }
  .button:active {
    box-shadow: inset 0px 1px 5px rgba(0, 0, 0, 0.2);
  }
  .button a {
    color: black;
    text-decoration: none;
  }
</style>

<script>
  function copyDOI3() {
    var doiLink = "http://hdl.handle.net/1959.7/uws:67799";
    copyToClipboard(doiLink);
  }
  function copyCitation3() {
    fetch('mphilthesis.bib')
      .then(response => response.text())
      .then(text => {
        copyToClipboard(text);
      })
      .catch(error => console.log(error));
  }
  function copyToClipboard(text) {
    var textarea = document.createElement("textarea");
    textarea.value = text;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand("copy");
    document.body.removeChild(textarea);
    alert("Copied to clipboard: " + text);
  }
</script>


<hr style="border:1px solid black">

<div style="padding: 20px; border-radius: 10px;">
  <div style="display: flex; align-items: stretch;">
    <div style="flex-grow: 1; display: flex; align-items: center; justify-content: center; background-color: #333; padding: 20px; border-radius: 10px;">
      <h1 style="font-size: 28px; margin: 0; color: white;">Characterization of Coated Piezo-resistive Fabric for Respiration Sensing</h1>
    </div>
    <img src="./../images/stretch.png" style="width: 250px; height: auto; margin-left: 20px;">
  </div>
  <div style="display: flex; flex-direction: column;">
    <p>
      International Conference on Electrical Engineering Research & Practice (ICEERP), 2019
    </p>
    <p><strong>Sami Arja</strong>, Titus Jayarathna, Felipe Ulloa, Gaetano Gargiulo, Paul Breen</p>
  </div>
  <div class="button-container" style="padding-top: 20px;">
    <button class="button" onclick="copyCitation2()" style="color: black; font-size: 20px;">Cite</button>
    <button class="button" onclick="copyDOI2()" style="color: black; font-size: 20px;">DOI</button>
    <button class="button"><a href="https://www.researchgate.net/profile/Titus-Nanda-Kumara/publication/338599389_Characterization_of_Coated_Piezo-resistive_Fabric_for_Respiration_Sensing/links/5e7aef2ea6fdcc57b7bbb8a9/Characterization-of-Coated-Piezo-resistive-Fabric-for-Respiration-Sensing.pdf" style="color: black; font-size: 20px;">PDF</a></button>
  </div>
</div>


<style>
  .button-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-bottom: 20px;
  }
  .button {
    background-color: #cccccc;
    border: none;
    color: white;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 25px;
    margin: 0;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
    box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.8);
  }
  .button:hover {
    background-color: #999999;
  }
  .button:active {
    box-shadow: inset 0px 1px 5px rgba(0, 0, 0, 0.2);
  }
  .button a {
    color: black;
    text-decoration: none;
  }
</style>

<script>
  function copyDOI2() {
    var doiLink = "10.1109/ICEERP49088.2019.8956989";
    copyToClipboard(doiLink);
  }
  function copyCitation2() {
    fetch('characterisation_fabric_band_ICREEP.bib')
      .then(response => response.text())
      .then(text => {
        copyToClipboard(text);
      })
      .catch(error => console.log(error));
  }
  function copyToClipboard(text) {
    var textarea = document.createElement("textarea");
    textarea.value = text;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand("copy");
    document.body.removeChild(textarea);
    alert("Copied to clipboard: " + text);
  }
</script>


<hr style="border:1px solid black">


<div style="padding: 20px; border-radius: 10px;">
  <div style="display: flex; align-items: stretch;">
    <div style="flex-grow: 1; display: flex; align-items: center; justify-content: center; background-color: #333; padding: 20px; border-radius: 10px;">
      <h1 style="font-size: 28px; margin: 0; color: white;">Characterization of morphic sensors for body volume and shape applications</h1>
    </div>
    <img src="./../images/ADC.png" style="width: 250px; height: auto; margin-left: 20px;">
  </div>
  <div style="display: flex; flex-direction: column;">
    <p>
      Sensors Journal, 2019
    </p>
    <p><strong>Sami Arja</strong>, Titus Jayarathna, Ganish Naik, Paul Breen, Gaetano Gargiulo</p>
  </div>
  <div class="button-container" style="padding-top: 20px;">
    <button class="button" onclick="copyCitation1()" style="color: black; font-size: 20px;">Cite</button>
    <button class="button" onclick="copyDOI1()" style="color: black; font-size: 20px;">DOI</button>
    <button class="button"><a href="https://pdfs.semanticscholar.org/5b6f/de4216f65d88bff0b6bbce2c31b687d410a1.pdf?_gl=1*11wka38*_ga*NjkwMDkyNDczLjE2ODIyNTY1Nzk.*_ga_H7P4ZT52H5*MTY4MjY1MTMwMC41LjAuMTY4MjY1MTY1OS4wLjAuMA" style="color: black; font-size: 20px;">PDF</a></button>
  </div>
</div>



<style>
  .button-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-bottom: 20px;
  }
  .button {
    background-color: #cccccc;
    border: none;
    color: white;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 25px;
    margin: 0;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
    box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.8);
  }
  .button:hover {
    background-color: #999999;
  }
  .button:active {
    box-shadow: inset 0px 1px 5px rgba(0, 0, 0, 0.2);
  }
  .button a {
    color: black;
    text-decoration: none;
  }
</style>

<script>
  function copyDOI1() {
    var doiLink = "https://doi.org/10.3390/s20010090";
    copyToClipboard(doiLink);
  }
  function copyCitation1() {
    fetch('characterisation_fabric_band.bib')
      .then(response => response.text())
      .then(text => {
        copyToClipboard(text);
      })
      .catch(error => console.log(error));
  }
  function copyToClipboard(text) {
    var textarea = document.createElement("textarea");
    textarea.value = text;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand("copy");
    document.body.removeChild(textarea);
    alert("Copied to clipboard: " + text);
  }
</script>


<hr style="border:1px solid black">
