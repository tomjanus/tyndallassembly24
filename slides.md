<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.14.0/devicon.min.css">

<!-- .slide: style="text-align: center;"> -->
<h3> Democratizing Reservoir Emission Models via <br><i style="color: #FF7A59">Open-Sourcing</i> and <i style="color: #FF7A59">Cloud-Computing</i> </h3>
<hr>
<h4>Free open tools for <u>large-scale</u> reservoir assessments and planning</h4>
<img src="images/upper_paunglaung.jpg" 
    style="float: center; border-radius: 5%; box-shadow: 0px 0px 10px rgba(255, 255, 255, 1)" height="270">

<a href="https://tomjanus.github.io/tyndallassembly24/">https://tomjanus.github.io/tyndallassembly24</a>

---

### Enablers of research software adoption

<img class="r-stretch" style="border-radius: 20px; box-shadow: 10px 10px 35px rgba(180, 180, 180, 0.35);" src="images/venn-diagram-open-source-computation.drawio.png" />

---

### Reservoir Emissions in a Nutshell
<style>
  /* Style for all logo images */
  .em-img-container img {
      opacity: 0.95;
      transition: transform 0.2s, opacity 0.2s; /* Smooth transition for effects */
  }

  /* Hover effect */
  .em-img-container a:hover img {
      opacity: 1; /* Full opacity on hover */
      transform: scale(1.02); /* Slightly enlarge on hover */
  }

  /* Click effect */
  .em-img-container a:active img {
      transform: scale(0.98); /* Slightly shrink on click */
  }
</style>

<div class="em-img-container">
<a href="https://tomjanus.github.io/reemission/theory.html" target="_blank">
<img class="r-stretch" style="border-radius: 20px; box-shadow: 10px 10px 35px rgba(180, 180, 180, 0.35);" src="images/reservoir_emissions.png" />
</a>
</div>

<div style="font-size:large">
<b>Landscape transformation from a river to a reservoir.</b> Source: Prairie et al. 2018 <em>What Does the Atmosphere See?</em> Ecosystems, 21(5):1058-1071, Aug 2018. URL: <a href="https://doi.org/10.1007/s10021-017-0198-9">https://doi.org/10.1007/s10021-017-0198-9</a>.
</div>

---

### Estimating reservoir emissions with g-res

<img class="r-stretch" style="border-radius: 20px; box-shadow: 10px 10px 35px rgba(180, 180, 180, 0.35);" src="images/g-res-screenshot.png" />

<div style="font-size:large">
<b>g-res tool.</b> The carbon calculator for reservoirs. URL:  <a href="https://www.grestool.org/">https://www.grestool.org/</a>.
</div>

---


## GeoCARET \& RE-Emission
<!-- .slide: style="text-align: center; font-size: 30px"> -->
<style>
  #left {
    left:-8.33%;
    text-align: justified;
    float: left;
    width:50%;
    z-index:-10;
  }

  #right {
    left:31.25%;
    top: 75px;
    float: right;
    text-align: justified;
    z-index:-10;
    width:50%;
  }

  img.software_logos {
    width: 450px;
    border-radius: 10px;
    opacity: 0.9;
  }

  /* Style for all logo images */
  .logo-container img {
      opacity: 0.8;
      transition: transform 0.2s, opacity 0.2s; /* Smooth transition for effects */
  }

  /* Hover effect */
  .logo-container a:hover img {
      opacity: 1; /* Full opacity on hover */
      transform: scale(1.05); /* Slightly enlarge on hover */
  }

  /* Click effect */
  .logo-container a:active img {
      transform: scale(0.95); /* Slightly shrink on click */
  }
</style>

<div id="left">
    <div class="logo-container">
    <!-- Content for the left column goes here -->
    <a href="https://github.com/Reservoir-Research/geocaret" target="_blank">
    <img style="opacity:0.95; border-radius: 70px;" src="images/graphical_abstract_ghg_left.drawio.png"/>
    </a>
    </div>
    <a style="font-size:24px" href="https://github.com/Reservoir-Research/geocaret">https://github.com/Reservoir-Research/geocaret</a>
</div>
<div id="right">
    <div class="logo-container">
    <a href="https://github.com/tomjanus/reemission" target="_blank">
    <img style="opacity:0.95; border-radius: 70px;" src="images/graphical_abstract_ghg_right.drawio.png"/>
    </a>
    </div>
    <a style="font-size:24px" href="https://github.com/tomjanus/reemission">https://github.com/tomjanus/reemission</a>
</div>

---

### Outsourcing computation and data storage

<img class="r-stretch" style="border-radius: 20px; box-shadow: 10px 10px 35px rgba(180, 180, 180, 0.35);" src="images/geocaret-gee-connections.drawio.png" />

---

## Containerising with <i class="devicon-docker-plain-wordmark"></i>
<!-- .slide: data-visibility="hidden" style="text-align: center; font-size: 30px;"> -->
<style>
  #left {
    left:-8.33%;
    text-align: justified;
    float: left;
    width:50%;
    z-index:-10;
  }

  #right {
    left:31.25%;
    top: 75px;
    float: right;
    text-align: justified;
    z-index:-10;
    width:50%;
  }

  .hljs {
    display: block;
    overflow-x: auto;
    line-height: 140%;
    font-size:16px;
  }
</style>

<div class="em-img-container">
<a href="https://reservoir-research.github.io/geocaret/installation/using_docker.html" target="_blank">
<img class="r-stretch" style="border-radius: 20px; box-shadow: 10px 10px 35px rgba(180, 180, 180, 0.35)" src="images/docker-explanation-wider.drawio.png" height=480px/>
</a>
</div>

---

<h3>Reservoir Emission<i style="color: #FF7A59"> Assessments</i></h3>

<iframe class="r-stretch" 
style="border-radius: 20px; box-shadow: 15px 15px 35px rgba(180, 180, 180, 0.35);"
src="map.html" frameborder="0" allowfullscreen>
</iframe>
<style>
  .left {
    text-align: left;
  }
</style>
<p style="font-size: 25px">Source: <a href="https://reservoir-research.github.io/ukreservoir-emissions/"> https://reservoir-research.github.io/ukreservoir-emissions/</a></p>

---

<h3>Reservoir<i style="color: #FF7A59"> Planning</i></h3>

<img class="r-stretch" style="border-radius: 20px; box-shadow: 10px 10px 35px rgba(180, 180, 180, 0.35);" src="images/planning-tyndall.png" />

---

### Further Work
<style>
  .fragment.blur {
    filter: blur(5px);
  }
  .fragment.blur.visible {
    filter: none;
  }
</style>
<section>
  <p>1. New applications for <a href="https://github.com/UoMResearchIT/geocaret/">GeoCARET</a></p>
  <p class="fragment custom blur">2. Supporting <a href="https://github.com/tomjanus/reemission/">Re-Emission</a> with Interpretations</b></p>
  <p class="fragment custom blur">3. Integration with other modelling frameworks</p>
  <p class="fragment custom blur">4. Engaging with users and stakeholders</p>
</section>

---

## Contributors

<!-- .slide: style="text-align: center; font-size: 30px"> -->
<style>
    img.faces {
    width: 110px;
    height: 110px;
    border-radius: 10%;
    }
</style>
<table>
  <tr>
    <td align="center"><img class="img custom faces" src="images/tomasz-cropped.jpg" alt=""/><br /><sub><b>Tomasz Janus</b> (Tyndall)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/jaise-cropped.jpg" alt=""/><br /><sub><b>Jaise Kuriakose</b> (Tyndall)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/boy.png" alt=""/><br /><sub><b>Chris Barry</b> (UKCEH)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/kamilla-cropped.jpg" alt=""/><br /><sub><b>Kamilla Kopec-Harding</b> (Research IT)</sub><br /></td>
    <td align="center"><img class="img custom faces" src="images/sinnott.jpeg" alt=""/><br /><sub><b>James Sinnott </b> (Resarch IT)</sub><br /></td>
  </tr>
</table>

<hr>
<br>

## Please visit us later for updates

<!-- <img src="images/qr_code.png" width=250px> -->

<a href="https://tomjanus.github.io/tyndallassembly24/">https://tomjanus.github.io/tyndallassembly24</a>
