---
layout: article
title: "INSAIT: INterpretable Systems for Artificial Intelligence Transparency"
excerpt: ICIAP 2025 Workshop
menu: true
show_info: true
titles:
  en      : &EN       Home
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
key: page-home
article_header:
  type: overlay
  theme: dark
  align: left
  actions:
    - text: September 15 or 16 (to be announced), 2025 | Rome, Italy 
  background_image:
    src: /assets/images/INSAIT_banner.png
    gradient: 'linear-gradient(135deg, rgb(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4))'
---

<style>
  
.schedule-table-heading {
    display: inline;
    font-weight: bold;
    font-size: 20px;
    color: #999999;
    padding:0 0 20px 0;
}

.schedule-table-timecol {
    padding:0 50px 0 50px;
    display:inline;
}

.schedule-table-eventcol {
    display:inline;
    display:inline-block;
    inline-size: 300px;
}

.schedule-table-contentcol {
    display:inline;
    display:inline-block;
    inline-size: 250px;
    font-size:14px;
    line-height: normal;
}

.schedule-table-row-even {
    display:block;
    width:800px;
    background-color: #EEEEEE;
    padding:10px;
}

.schedule-table-row-odd {
    display:block;
    width:800px;
    padding:10px;
}

.article__header--overlay .overlay {
    min-height: 36rem;
    padding-top: 5rem;
    padding-bottom: 5rem;
}

.article__header {
    margin: 0 0 0 0;
}

.article__header h1 {
    display: inline;
    font-family: sans-serif;
    font-size: 2em;
    letter-spacing: -0.04em;
    line-height: 0.9;
    color: white;
    /*text-shadow: -20px -8px 17px rgb(0 0 0 / 90%);
    -webkit-text-stroke: 2px black; /* width and color */
    word-wrap: break-word;
}

.overlay__excerpt {
    margin: 20px 0 0 0;
    font-family: sans-serif;
    color: white;
    /*text-shadow: -20px -8px 17px rgb(0 0 0 / 90%);*/
}

ul.menu li::after {
    color: white;
    /*text-shadow: -20px -8px 17px rgb(0 0 0 / 90%);*/
    content:"September 15 or 16 (to be announced), 2025 | Rome, Italy";
}

ul.menu a {
    display: none;
}

.pc-column {
    width:270px;
    display:inline-block;
    vertical-align: top;
}

.pc_list_item {
    display:inline-block;
    width:200px;
}

.organiser_profile {
    font-weight:normal;
    color: black;
}

.organiser_profile a:link a:visited a:hover a:active {
    font-weight:normal;
    color: #000000;
}

.organiser_profile p {
    font-weight:normal;
    color: #000000;
}

.logos-organizers {
    display: flex;
    align-items: center;
    flex-direction: row;
    flex-wrap: nowrap;
}

.img-fluid {
    max-width: 100%;
    height: auto;
}

img {
    vertical-align: middle;
    border-style: none;
}

body {
  font-family: 'Arial', sans-serif;
  line-height: 1.6;
  color: #333;
}

  .reviewers-container {
    display: flex;
    flex-wrap: wrap;
  }

  .reviewers-container > div {
    padding: 5px;
    background-color: #f0f0f0;
    border-radius: 5px;
    margin: 5px;
  }

  .sponsor-logos img {
    width: 150px; /* Adjust this value as needed */
    margin-right: 20px; /* Space between images */
}

/* Remove margin from the last image */
.sponsor-logos img:last-child {
    margin-right: 0;
}

.toggle-button {
    background-color: #007bff; /* Blue background */
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    outline: none;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.toggle-button::after {
    content: ' ▼'; /* Down arrow by default */
}

.toggle-button.active::after {
    content: ' ▲'; /* Up arrow when the section is visible */
}


/* Optional: Style for paper titles */
.paper-title {
    font-weight: bold;
}

/* Optional: Style for authors */
.authors {
    font-style: italic;
}

table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }

       .time {
            font-weight: bold;
            text-align: center;
        }
  
</style>


<!-- <script>

  
  var x = setInterval(function() {
    var d = new Date();
    var n = d.toLocaleTimeString("en-US", {timeZone: "America/New_York", hour: '2-digit', minute:'2-digit', hour12: false})
    document.getElementById("edt").innerHTML = n
  }, 1000);
</script>

<script>
  var x = setInterval(function() {
    var d = new Date();
    var n = d.toLocaleTimeString("en-US", {timeZone: "Europe/Vienna", hour: '2-digit', minute:'2-digit', hour12: false})
    document.getElementById("cet").innerHTML = n
  }, 1000);
</script>

<script>
  {%- include scripts/lib/swiper.js -%}
  var SOURCES = window.TEXT_VARIABLES.sources;
  window.Lazyload.js(SOURCES.jquery, function() {
    $('.swiper-demo').swiper();
  });
</script>

<script>

  var countDownDate = new Date("Feb 15, 2022 23:59:59 UTC").getTime();  
  countDownDate = countDownDate + 1000 * 3600 * 12


  var x = setInterval(function() {


    var now = new Date().getTime();


    var distance = countDownDate - now;


    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);


    var countdown = days + "d " + hours + "h " + minutes + "m " + seconds + "s ";


    if (distance < 0) {
      clearInterval(x);
      countdown = "(expired)";  
    }

    document.getElementById("countdown").innerHTML = countdown

  }, 1000);
</script> -->

<br>

## About

Artificial Intelligence (AI) innovations have led to increasingly complex models, such as foundational and generative multimodal models. They achieve state-of-the-art performance across various domains, however, their black-box nature raises concerns about their trust, accountability, and ethical deployment. The INSAIT Workshop (INterpretable Systems for Artificial Intelligence Transparency) aims to bring together researchers and practitioners to explore interpretability in AI, focusing on methods that enhance transparency, explainability, and human-centric trust. Understanding why AI systems work so well and why they fail is important for their integration into real-world applications used by millions of people.

## Call for papers

This workshop invites contributions from academia and industry on theoretical and practical topics including, but not limited to:

<div>
<div style="width:49%; display:inline-block; font-size:14px; vertical-align:top">
<ul>
<li><strong>Explanation methods</strong>: post-hoc interpretability techniques (e.g., SHAP, LIME, attention-based explanations, mechanistic interpretability, etc.).</li>
<li><strong>Interpretability by design</strong>: design of inherently interpretable architectures (e.g., prototype-based, capsule networks, concept bottleneck models).
</li>
<li><strong>Concept learning and unlearning techniques</strong>: for example, how removing unwanted concepts impacts a model.</li>
<li><strong>Human-AI interaction</strong>: how interpretability improves user trust and decision-making.</li>
</ul>
</div>
<div style="width:49%; display:inline-block; font-size:14px; vertical-align:top">
<ul>
<li><strong>Benchmarking interpretability</strong>: standardized evaluation metrics for explainability.</li>
<li><strong>Ethical & societal implications</strong>: ensuring fairness, accountability, and transparency through interpretability.</li>
<li><strong>Case studies</strong>: applications of interpretability in healthcare, finance, legal systems, and autonomous systems.</li>
</ul>
</div>
</div>

### Paper submissions

All submissions will go through a double-blind review process. Papers will be selected based on relevance, significance, novelty of results, technical merit, and clarity of presentation. Only previously unpublished works will be considered.

There are two tracks for submission to INSAIT:

<p><strong>Proceedings track</strong>: Submitted papers to the proceedings track <strong>must not exceed 12 pages (including references)</strong>. Accepted papers will be published in a dedicated volume of Springer Lecture Notes in Computer Science (LNCS).</p>

<p><strong>Extended abstract track</strong>: In this track, we invite papers <strong>up to 6 pages (including references)</strong> for presenting high-impact, innovative ideas or work-in-progress that may not be ready for full publication.</p>

Submissions to both tracks will be featured during the workshop's poster session, and a subset of all submissions will be selected for spotlight talks. Papers must be in English.

Each accepted paper must be covered by at least one author registration (either a Full registration or a Workshop/Tutorial registration if you plan to attend the workshops/tutorials only).

We suggest workshop papers are prepared and submitted using the official <a href="https://drive.google.com/file/d/1NxtKBIzZARUUNeNuCUNIA6XtQ0RtL1NI/view?usp=sharing">ICIAP template</a> (there is also this <a href="https://www.overleaf.com/read/bpkfqrbhcrcg">Overleaf template</a>).

Please submit your papers in PDF format through Openreview (link coming soon).

## Important Dates

Submission deadline - June 7 (23:59 AoE), 2025 \
Author notification - July 01 (23:59 AoE), 2025 \
Camera ready deadline -  July 10 (23:59 AoE), 2025 

Note: all deadlines are in <b>Anywhere on Earth (AoE)</b>.

## Workshop Event

<b>When:</b> September 15 or 16 (to be announced), 2025 \
<b>Where:</b> Sapienza University of Rome, Piazzale Aldo Moro 5, 00185 Rome

## Registration

For detailed instructions and information on registration fees, please visit the <a href="https://sites.google.com/view/iciap25/registration">ICIAP registration page</a>.

## Schedule

To be announced.

## Speakers


<div style="display:inline; width:900px; vertical-align: top;">

<a href="https://www.eml-munich.de/people/stephan-alaniz" target="_blank" class="speaker_profile">
  <div style="display:inline-block; width:270px; margin:20px 0 0 0;">
    <div style="display:inline-block; width:101px;">
      <img 
        style="width:100px; height:100px; position: relative; bottom: 20px; border-radius: 50%;" 
        src="{{ site.baseurl }}/assets/images/speakers/stephan-alaniz.png" 
        alt="Stephan Alaniz">
    </div>
    <div style="display:inline-block; width:150px; line-height:1.4; color:black;">
      <p style="margin:0 0 0 10px;">Stephan Alaniz</p>
      <p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>Explainable AI</p>
    </div>
  </div>
</a>

</div>


## Organizers

<div style="display:inline; width:900px; vertical-align: top;">

<a href="https://www.linkedin.com/in/riccardo-renzulli/" target="_blank" class="organiser_profile">
  <div style="display:inline-block; width:270px; margin:20px 0 0 0;">
    <div style="display:inline-block; width:101px;">
      <img 
        style="width:100px; height:100px; position: relative; bottom: 40px; border-radius: 50%;" 
        src="{{ site.baseurl }}/assets/images/organizers/riccardo_renzulli.png" 
        alt="Riccardo Renzulli">
    </div>
    <div style="display:inline-block; width:150px; line-height:1.4; color:black;">
      <p style="margin:0 0 0 10px;">Riccardo Renzulli</p>
      <p style="margin:0 0 0 10px; font-size:10px;">Postdoc at University of Turin, his interests lie in representation learning, interpretability, medical imaging</p>
    </div>
  </div>
</a>

<a href="https://www.linkedin.com/in/eleonora-poeta/" target="_blank" class="organiser_profile">
  <div style="display:inline-block; width:270px; margin:20px 0 0 0;">
    <div style="display:inline-block; width:101px;">
      <img 
        style="width:100px; height:100px; position: relative; bottom: 40px; border-radius: 50%;" 
        src="{{ site.baseurl }}/assets/images/organizers/eleonora_poeta.png" 
        alt="Eleonora Poeta">
    </div>
    <div style="display:inline-block; width:150px; line-height:1.4; color:black;">
      <p style="margin:0 0 0 10px;">Eleonora Poeta</p>
      <p style="margin:0 0 0 10px; font-size:10px;">PhD student at Politecnico di Torino, her interests lie in trustworthy AI, explainable AI, fairness</p>
    </div>
  </div>
</a>

<a href="https://www.linkedin.com/in/francesca-naretto-710bb31a2/" target="_blank" class="organiser_profile">
  <div style="display:inline-block; width:270px; margin:20px 0 0 0;">
    <div style="display:inline-block; width:101px;">
      <img 
        style="width:100px; height:100px; position: relative; bottom: 40px; border-radius: 50%;" 
        src="{{ site.baseurl }}/assets/images/organizers/francesca_naretto.png" 
        alt="Francesca Naretto">
    </div>
    <div style="display:inline-block; width:150px; line-height:1.4; color:black;">
      <p style="margin:0 0 0 10px;">Francesca Naretto</p>
      <p style="margin:0 0 0 10px; font-size:10px;">Researcher at the University of Pisa, her interests lie in explainable artificial intelligence, data privacy and federated learning</p>
    </div>
  </div>
</a>

<a href="https://www.linkedin.com/in/mirkozaff/" target="_blank" class="organiser_profile">
  <div style="display:inline-block; width:270px; margin:20px 0 0 0;">
    <div style="display:inline-block; width:101px;">
      <img 
        style="width:100px; height:100px; position: relative; bottom: 40px; border-radius: 50%;" 
        src="{{ site.baseurl }}/assets/images/organizers/mirko_zaffaroni.png" 
        alt="Mirko Zaffaroni">
    </div>
    <div style="display:inline-block; width:150px; line-height:1.4; color:black;">
      <p style="margin:0 0 0 10px;">Mirko Zaffaroni</p>
      <p style="margin:0 0 0 10px; font-size:10px;">Researcher at CentAI, his interests lie in explainable AI, synthetic data and multimodal feature fusion</p>
    </div>
  </div>
</a>

<a href="https://www.linkedin.com/in/alan-perotti-phd-146b4037/" target="_blank" class="organiser_profile">
  <div style="display:inline-block; width:270px; margin:20px 0 0 0;">
    <div style="display:inline-block; width:101px;">
      <img 
        style="width:100px; height:100px; position: relative; bottom: 40px; border-radius: 50%;" 
        src="{{ site.baseurl }}/assets/images/organizers/alan_perotti.png" 
        alt="Alan Perotti">
    </div>
    <div style="display:inline-block; width:150px; line-height:1.4; color:black;">
      <p style="margin:0 0 0 10px;">Alan Perotti</p>
      <p style="margin:0 0 0 10px; font-size:10px;">Senior researcher at CentAI, his interests lie in representation learning, interpretability, industry</p>
    </div>
  </div>
</a>



</div>

## Program Committee
<div id="all-reviewers-list" style="display: block;">
<div><strong>Marco Grangetto</strong>, University of Turin</div>
<div><strong>Enrico Cassano</strong>, University of Turin</div>
<div><strong>Elvio Amparore</strong>, University of Turin</div>
<div><strong>Muhammad Rashid</strong>, University of Turin</div>
<div><strong>Marco Nurisso</strong>, Politecnico di Torino</div>
<div><strong>Georgios Leontidis</strong>, University of Aberdeen</div>
<div><strong>Aiden Durrant</strong>, University of Aberdeen</div>
<div><strong>Sonia Laguna Cillero</strong>, ETH Zurich</div>
<div><strong>Enzo Tartaglione</strong>, Télécom Paris, Institut Polytechnique de Paris</div>
<div><strong>Julia Herbinger</strong>, Leibniz Institute for Agricultural Engineering and Bioeconomy</div>
<div><strong>Lenka Tětková</strong>, University of Denmark</div>
<div><strong>Arianna Casanova Flores</strong>, Universität Liechtenstein</div>
<div><strong>Maximilian Dreyer</strong>, Fraunhofer Heinrich Hertz Institute</div>
<div><strong>Eliana Pastor</strong>, Politecnico di Torino</div>
<div><strong>Salvatore Greco</strong>, Politecnico di Torino</div>
<div><strong>Lia Morra</strong>, Politecnico di Torino</div>
<div><strong>Valentina Ghidini</strong>, Duferco</div>
<div><strong>Giulia Vilone</strong>, Analog Devices</div>
.. (to be updated)
</div>

# Contact information

- Email: INSAIT.workshop [AT] gmail.com
- X: [@INSAIT_workshop](https://twitter.com/INSAIT_workshop)


## Organized by

<div class="organizers-logos">
    <img style="height: 75px; margin: 0 10px;" src="{{ site.baseurl }}/assets/images/sponsors/unito_logo.png" alt="UNITO Logo">
    <img style="height: 75px; margin: 0 10px;" src="{{ site.baseurl }}/assets/images/sponsors/polito_logo.png" alt="POLITO Logo">
    <img style="height: 75px; margin: 0 10px;" src="{{ site.baseurl }}/assets/images/sponsors/unipi_logo.png" alt="UNIPI Logo">
    <img style="height: 75px; margin: 0 10px;" src="{{ site.baseurl }}/assets/images/sponsors/centai_logo.png" alt="CentAI Logo">
</div>
