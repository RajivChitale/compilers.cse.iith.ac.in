---
title: "Polyhedral Model Guided Automatic GPU Cache Exploitation Framework"
redirect_from:
    - /publications/polyhedralmodelguided
layout: textlay
excerpt: "IITH Compilers Team -- Publications"
sitemap: false
permalink: /projects/polyhedralmodelguided/
---


<div class="container-fluid" style="height:100%; width:100%"> 
<h1>Polyhedral Model Guided Automatic GPU Cache Exploitation Framework</h1>
<p>Abhishek A Patwardhan and <a href="https://www.iith.ac.in/~ramakrishna" target="_blank">Ramakrishna Upadrasta</p>
<h4> Published at IEEE International Conference on High Performance Computing & Simulation, Spl Compiler Design And Optimization Session, Dublin, Ireland, 2019</h4>
 
 <br>

 <div style="position:relative; top:-25px;">
 <h4><a href="https://ieeexplore.ieee.org/document/9188095" target="_blank">Paper</a>
 &nbsp;
 <a href= "https://github.com/abhishek111226/Texturizing-PPCG" target="_blank">
 <img class="dp-img" alt="OpenMp_Github" src="https://github.githubassets.com/favicons/favicon.svg" width="23px" height="23px" />
 </a> 
  </h4>
 </div>
 
<p>We propose a compiler driven acceleration of parallel computations on GPUs by exploiting the various special varieties of caches (texture, surface and constant for NVIDIA GPUs). We show that our method obtains better performance for a class of computations when compared with earlier methods that use on-chip shared memory. We provide an end-to-end solution by developing a fully automatic, sound, static framework within a state-of-art source-to-source Polyhedral compiler (PPCG) to exploit these varieties of GPU caches. We use polyhedral model for profitability modeling of the particular variety of GPU caches. We evaluate our implementation on PolyBench/C benchmark kernels and report up to 1. 5x speedups over the current memory mapping strategy used by PPCG compiler. We also consider sample real-world representative kernels: PageRank, DNN layer (LSTM), solvers (Poisson and DWE-FDTD stencil), and show that using the special GPU caches in these programs results in up to 2. 6x speedup over a standard shared memory based implementation. We believe that our contribution is towards automatic exploitation of GPU cache/memory hierarchy as it shows general purpose computing usage of special GPU caches that were originally designed for image processing applications.</p>
<br>
</div>