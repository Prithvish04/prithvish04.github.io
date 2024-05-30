---
permalink: "/publication/"
layout: page
title: Publications
sidebar_link: true
order: 2
---


<style>

table {
  margin-bottom: 1rem;
  width: 100%;
  font-size: 85%;
  border: 0px solid $border-color;
  border-collapse: collapse;
}

td,
th {
  padding:  1rem .25rem;
  border: 0px solid $border-color;
}

th {
  text-align: left;
}

tbody tr:nth-child(odd) td,
tbody tr:nth-child(odd) th {
  background-color: transparent;
}

paper {
 color: #; 
 font-weight:bold;
}


</style>
#### 2023 - 2024

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">

  <tr>
       <td width="14%"  valign="top">
            <img src="/images/publications/sensim.png" alt="SENSIM" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
            <paper> SENSIM: An Event-driven Parallel Simulator for Multi-core Neuromorphic Systems </paper>
              <br>  
              <b>Prithvish V N</b>*,    
            <br>
            IEEE WCCI International Joint Conference on Neural Networks (IJCNN 2024)
              <details>
                <summary>Abstract  |  <a href="https://github.com/Prithvish04/SENSIM_paper_submission/blob/main/docs/SENSIM_paper_sub_1570986279.pdf">Paper</a> |  <a href="https://www.youtube.com/watch?v=mfZOLWlofaQ">Video</a> | <a href="https://github.com/Prithvish04/SENSIM_paper_submission/blob/main/docs/SENSIM_poster.pdf">Poster</a> | <a href="https://github.com/Prithvish04/SENSIM_paper_submission/blob/main/docs/SENSIM_Slides.pdf">slides</a>  </summary>          
                  <p class="message">
                  In this paper, we present SENSIM, which is an open-source simulator designed specifically for the SENECA neuromorphic processor. This simulator is unique in that it combines features from both hardware-specific and hardware-agnostic spiking neural network simulators, resulting in a hybrid event-driven and time-step-driven simulation approach. This allows for flexibility between accuracy and speed during different stages of simulation. Our work highlights the open-source SENSIM platform, which enables the mapping of large-scale SNN/DNN models to the SENECA cores, as well as the benchmarking of crucial KPIs such as power and latency estimations\footnote{Source code of the simulator can be found in 
                  </p>
              </details>
          </p>  
     </td>
  </tr> 

<tr>
       <td width="14%"  valign="top">
            <img src="/images/publications/seneca.png" alt="FON" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Optimizing event-based neural networks on digital neuromorphic architecture: a comprehensive design space exploration</paper>
              <br>  
              <b>Prithvish V N</b>, <a href="">Kevin Shidqi</a>,
<a href="">GertJan van Schaik</a>,
<a href="">Refik Bilgic</a>,
<a href="">Alexandra Dobrita</a>,
<a href="">Shenqi Wang</a>,
<a href="">Roy Meijer</a>,
<a href="">Yingfu Xu</a>,
<a href="">Cina Arjmand</a>,
<a href="">Pietro Martinello</a>,
<a href="">Anteneh Gebregiorgis</a>,
<a href="">Said Hamdioui</a>,
<a href="">Paul Detterer</a>,
<a href="">Stefano Traferro</a>,
<a href="">Mario Konijnenburg</a>,
<a href="">Kanishkan Vadivel</a>,
<a href="">Manolis Sifalakis</a>,
<a href="">Guangzhi Tang</a>,
<a href="">Amirreza Yousefzadeh</a>.
            <br>
            Frontiers of Neuroscience Volume 18 (2024)
              <details>
                <summary>Abstract  | <a href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2024.1335422/full">Paper</a>  </summary>            
                  <p class="message">
                  Neuromorphic processors promise low-latency and energy-efficient processing by adopting novel brain-inspired design methodologies. Yet, current neuromorphic solutions still struggle to rival conventional deep learning accelerators' performance and area efficiency in practical applications. Event-driven data-flow processing and near/in-memory computing are the two dominant design trends of neuromorphic processors. However, there remain challenges in reducing the overhead of event-driven processing and increasing the mapping efficiency of near/in-memory computing, which directly impacts the performance and area efficiency. In this work, we discuss these challenges and present our exploration of optimizing event-based neural network inference on SENECA, a scalable and flexible neuromorphic architecture. To address the overhead of event-driven processing, we perform comprehensive design space exploration and propose spike-grouping to reduce the total energy and latency. Furthermore, we introduce the event-driven depth-first convolution to increase area efficiency and latency in convolutional neural networks (CNNs) on the neuromorphic processor. We benchmarked our optimized solution on keyword spotting, sensor fusion, digit recognition and high resolution object detection tasks. Compared with other state-of-the-art large-scale neuromorphic processors, our proposed optimizations result in a 6× to 300× improvement in energy efficiency, a 3× to 15× improvement in latency, and a 3× to 100× improvement in area efficiency. Our optimizations for event-based neural networks can be potentially generalized to a wide range of event-based neuromorphic processors.
                  </p>
              </details>
          </p>  
     </td>
  </tr> 

   <tr>
    <td width="14%"  valign="top">
            <img src="/images/publications/mapper.png" alt="mapper" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Efficient mapping of large scale SNN and rate-based DNN on SENeCA</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
            Delft University of Technology, Library
              <details>
                <summary>Abstract  | <a href="https://repository.tudelft.nl/islandora/object/uuid%3A97c7e7f6-a482-4e42-aa95-b0d58c09a054">Master Thesis</a>  </summary>            
                  <p class="message">
Artificial intelligence, machine learning, and deep learning have been the buzzwords in almost every industry (medical, automotive, defense, security, finance, etc.) for the last decade. As the market moves towards AI-based solutions, so does the computation need for these solutions increase and change with time. With the rise of smart cities and cyberphysical systems, the need for edge devices and efficient computation on the edge increases. While most of these newly developed deep learning models are quite large and wasteful in terms of energy, there have been recent methods that help improve the performance on the edge. However, due to their size, variety, and irregularity, the computing and power requirements are often too large to deploy these models on edge devices. This prohibits the application of such models within a rich field of application that requires high-throughput and real-time execution.

SENeCA (Scalable Energy Efficient Neuromorphic Computing Architecture) is a next-generation RISC-V-based neuromorphic computing architecture that was designed primarily for ultralow-edge applications where adaptivity is required. To mathematically model SENeCA, SENSIM (Scalable Energy Efficient Simulator, an open source simulator developed by the Interuniversity Microelectronic Center) provides an accurate mathematical software model of SENeCA, which helps in the early development and realization of a spiking neural network and deep neural network. This thesis work develops an efficient mapping tool SENMap (Scalable Energy-Efficient Neuromorphic Computing Architecture Mapper) on top of SENSIM which maps spiking neural networks efficiently. Having a faster, scalable realization software solution that can cater to large-scale neural networks can speed up the development procedure.

SENMap is developed in such a way that it supports flexible SNN/DNN application replacement, multiple single- and multi-objective optimization algorithms; the flexibility to choose from different optimization strategies; and also varying architectural parameters at the time of experimentation. Results show that mapping and neural processing elements (NPEs) depend primarily on the rate at which the sensor processes the data. On the basis of the rate, an early realization of SNN- and DNN-based edge AI chips SENMap. Depending on the actual parameters used, the maximum achieved improvements in energy consumption was around ~40%.
                  </p>
              </details>
          </p>  
     </td>
  </tr> 

 
</table>

#### 2017-2018

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">

 <tr>
    <td width="14%"  valign="top">
      <img src="/images/publications/smartcart.png" alt="smartcart" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
          <paper>An IoT-Based Smart Shopping Cart Using the Contemporary Barcode Scanner</paper>
              <br>  
              <b>Prithvish V N</b>, Shraddha Agrawal, John Sahaya Rani Alex   
            <br>
            Springer Lecture Notes on electrical engineering, Intelligent Embedded systems
              <details>
                <summary>Abstract  | <a href="https://link.springer.com/chapter/10.1007/978-981-10-8575-8_6">Paper</a> </summary>           
                  <p class="message">
                  An efficacious prototyping of an intelligent Internet of Things (IoT)-based smart cart that primarily enhances the shopping experience of the customers as well as owners. The assembly of the smart cart consists of a contemporary barcode scanner from the present-day shopping scenario, feedback systems providing product weight and product imaging to avoid discrepancies, a cloud-based database and an embedded hardware to connect the above. The mechanism facilitates the customer to add and remove products throughout the shopping, updating the bill instantaneously, and further reflecting changes in the inventory. The framework incorporates a Parse cloud-based inventory to ease the managerial task at the owner end. Further focus has been also given on the proper placement of all the components on a cart for the efficient working of the shop, keeping user’s ease of usage in mind.
                  </p>
              </details>
          </p> 
     </td>
  </tr> 
</table>
 