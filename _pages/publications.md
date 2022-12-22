---
layout: archive
title: "Selected publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

<ul style="list-style-type:circle;"></ul>

<h1 class="year">2022</h1> 

 <ul>
     <li><a href="https://www.mdpi.com/1424-8220/22/22/8846" style="color: #B509AC; text-decoration:none;" target="\_blank">Supervised object-specific distance estimation from monocular images for autonomous driving</a>
<br><strong>Yury Davydov</strong>, Wen-Hui Chen, Yu-Chen Lin<br><em>MDPI, 2022, <b> DOI: </b><a href="https://www.mdpi.com/1424-8220/22/22/8846" style="color: #091AB5; text-decoration:none;" target="\_blank">10.3390/s22228846</a>.</em></li>


<p><i class="fas fa-globe" style="color:Blue"></i> <a href="https://www.mdpi.com/1424-8220/22/22/8846" style="color: blue; text-decoration:none;" target="\_blank"><strong>MDPI</strong></a> | <i class="fas fa-file-pdf" style="color:red"></i> <a href="https://www.mdpi.com/1424-8220/22/22/8846/pdf" style="color: red; text-decoration:none;" target="\_blank"><strong>PDF</strong></a> | <button onclick="myFunction()" id="myBtn">Show Abstract</button></p>
 
<style>
#more {display: none;}
</style> 
 
<span id="dots"></span><span id="more">


<p align="justify"><b>Abstract:</b> Accurate distance estimation is a requirement for advanced driver assistance systems (ADAS) to provide drivers with safety-related functions such as adaptive cruise control and collision avoidance. Radars and lidars can be used for providing distance information; however, they are either expensive or provide poor object information compared to image sensors. In this study, we propose a lightweight convolutional deep learning model that can extract object-specific distance information from monocular images. We explore a variety of training and five structural settings of the model and conduct various tests on the KITTI dataset for evaluating seven different road agents, namely, person, bicycle, car, motorcycle, bus, train, and truck. Additionally, in all experiments, a comparison with the Monodepth2 model is carried out. Experimental results show that the proposed model outperforms Monodepth2 by 15% in terms of the average weighted mean absolute error (MAE).</p></span></ul>


<script>
function myFunction() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Show Abstarct"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Hide Abstarct"; 
    moreText.style.display = "inline";
  }
}
</script>

<h1 class="year">2021</h1>

 <ul>
     <li><a href="https://www.mdpi.com/2227-7390/9/24/3237" style="color: #B509AC; text-decoration:none;" target="\_blank">Modeling the Dynamics of Spiking Networks with Memristor-Based STDP to Solve Classification Tasks</a>
      <br>Alexander Sboev, Danila Vlasov, Roman Rybka, <strong>Yury Davydov</strong>, Alexey Serenko, Vyacheslav Demin<br><em>MDPI, 2022, <b> DOI: </b><a href="https://www.mdpi.com/2227-7390/9/24/3237" style="color: #091AB5; text-decoration:none;" target="\_blank">10.3390/math9243237</a>.</em></li>
 
 <p><i class="fas fa-globe" style="color:Blue"></i> <a href="https://www.mdpi.com/2227-7390/9/24/3237" style="color: blue; text-decoration:none;" target="\_blank"><strong>MDPI</strong></a> | <i class="fas fa-file-pdf" style="color:red"></i> <a href="https://www.mdpi.com/2227-7390/9/24/3237/pdf" style="color: red; text-decoration:none;" target="\_blank"><strong>PDF</strong></a> | <button onclick="myFunction3()" id="myBtn3">Show Abstract</button></p>
 
<span id="dots3"></span><span id="more3">

 <script>
  if (document.getElementById("dots3").style.display != "none"){
  document.getElementById("dots3").style.display = "inline";
  document.getElementById("more3").style.display = "none";
  }
 </script>

<p align="justify"><b>Abstract:</b>The problem with training spiking neural networks (SNNs) is relevant due to the ultra-low power consumption these networks could exhibit when implemented in neuromorphic hardware. The ongoing progress in the fabrication of memristors, a prospective basis for analogue synapses, gives relevance to studying the possibility of SNN learning on the base of synaptic plasticity models, obtained by fitting the experimental measurements of the memristor conductance change. The dynamics of memristor conductances is (necessarily) nonlinear, because conductance changes depend on the spike timings, which neurons emit in an all-or-none fashion. The ability to solve classification tasks was previously shown for spiking network models based on the bio-inspired local learning mechanism of spike-timing-dependent plasticity (STDP), as well as with the plasticity that models the conductance change of nanocomposite (NC) memristors. Input data were presented to the network encoded into the intensities of Poisson input spike sequences. This work considers another approach for encoding input data into input spike sequences presented to the network: temporal encoding, in which an input vector is transformed into relative timing of individual input spikes. Since temporal encoding uses fewer input spikes, the processing of each input vector by the network can be faster and more energy-efficient. The aim of the current work is to show the applicability of temporal encoding to training spiking networks with three synaptic plasticity models: STDP, NC memristor approximation, and PPX memristor approximation. We assess the accuracy of the proposed approach on several benchmark classification tasks: Fisher’s Iris, Wisconsin breast cancer, and the pole balancing task (CartPole). The accuracies achieved by SNN with memristor plasticity and conventional STDP are comparable and are on par with classic machine learning approaches.</p></span></ul>

<script>
function myFunction3() {
  var dots = document.getElementById("dots3");
  var moreText = document.getElementById("more3");
  var btnText = document.getElementById("myBtn3");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Show Abstract"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Hide Abstract"; 
    moreText.style.display = "inline";
  }
}
</script>


