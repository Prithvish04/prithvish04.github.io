---
permalink: "/projects/"
layout: page
title: Projects
sidebar_link: true
order: 3
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
#### 2020-2022

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
   <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/cannyedge.png" alt="cannyedge" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Canny Edge Detector Algorithm acceleration on an FPGA</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="">Code & Report</a>  </summary>            
                <p class="message">
                The project covers a successful implementation of Canny edge detection in software as well as in hardware. Software implementation is used as a reference to evaluate the correctness and performance of the design. It can be concluded from the results of the design that the correctness reduces due to limited registers in the FPGA, which does not allow complete partitioning of the buffer in the Hysteresis stage. The performance increases significantly by optimizing the Sobel filter using the CORDIC algorithm, pipelining the operations, using intermediate arrays, and removing false dependencies.

                The goal of the project is to analyze the advantages and disadvantages of real-time video streaming applications using FPGA by accelerating Canny edge detection. The main advantage is the speedup of the process. The performance increased significantly compared to the software-implemented Canny edge detection. However, the image is shifted due to buffering of the input pixels. The main disadvantages are the shifted output image and reduction in the correctness of the image.

                There are three improvements suggested for future work: partial processing on CPU, dynamic thresholding, and improving Gaussian stage implementation. First, Canny edge detection with other algorithms that rely on edge detection, such as Hough transforms or image segmentation for machine learning, can be partially divided between the processor and the FPGA to reap the full benefits of hardware/software co-design. Second, the two thresholds at the Double-threshold stage can be determined dynamically based on the complexity of the provided image or frame. Finally, after optimizing the Sobel filter implementation using the CORDIC algorithm, it can be seen that the Gaussian block is the most time and area-consuming. This stage can be optimized dynamically based on the complexity of the provided image or frame.
                </p>
              </details>
          </p>  
     </td>
  </tr> 
  
  <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/low_power_mips.png" alt="low_power_mips" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Low power MIPS Architecture </paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="">Code & Report</a> </summary>
                  <p class="message">
                  This project aims to lay out the changes made to a simple MIPS architecture processor in order to improve severalperformance metrics of it such as speed, energy use and power consumption, as well as area. For this reportin particular the decreasing energy consumption while maintaining decent performance was considered aboveall. To that end, three major parts of the original processor were modified. Those were the cache hierarchy,the adder module for the alu and also the multiplier unit. In this report through design space exploration thebest cache configuration was found, resulting in about 3.2 Joules saved and 2.8 million cycles less. Finally, afterdoing research, the best options for the other two changes were found. Where after a radix-4 multiplier anda prefix adder were implemented. A final processor capable of running the benchmarks in 4948 million cycleswith only 7.59 Joules was achieved.
                  </p>
              </details>
          </p>  
     </td>
  </tr> 
 
 <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/ethereal.png" alt="ethereal" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Optimizing the Ethereal Engine Version 1 EtherealMatter</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="">Report</a> | <a href="">Poster</a> </summary>            
                  <p class="message">
Worldwide obesity has nearly tripled since 1975 and is still growing . More than a quarter of the world’s adult population is physically inactive, which has resulted in poor health systems and negative impacts on well-being . Physical activity has been shown to have significant health benefits for hearts, bodies, and minds, as it prevents noncommunicable diseases, reduces symptoms of depression and anxiety, and improves overall well-being . Still, more than 80% of the world’s adolescent population and 20% of the adult population are not sufficiently physically active . In particular, technological advancements in the gaming industry have led to a larger number of people, including children, spending time on video games rather than engaging in physical exercises. The rising adoption of a sedentary lifestyle increases the risk of non-communicable diseases such as type 2 diabetes and obesity. 

Interactive fitness products try to fight this increasing problem by introducing technology to the fitness industry market, making workouts safer, more fun, and flexible. This so-called exergaming is considered the most promising product as physical exercises are combined with video games to help people build up their strength and improve their fitness levels. One of the companies involved in this exergaming industry is Ethereal Matter, whose vision is to create "a full-body, intelligent fitness platform enabling immersive virtual-physical interaction, adaptable to the range of humanity who desire the benefits of improved health." To achieve this vision, a prototype called the "Ethereal Engine" was created. In this engine, games can be played by the end-user while working out and even being social with friends and family all over the world through virtual reality (VR). The machine consists of two robot armatures that the user can steer to move in the VR and that can also provide resistance to activate the muscles. However, the prototype still faces many challenges, and since Ethereal Matter is a start-up company with limited engineering resources, this is where we, as an interdisciplinary team of engineers, can contribute.

Due to the 10-week time constraint, the team decided to focus on improving the armatures of the existing prototype. The goal of this project is to tackle the challenges related to the armatures and deliver a concept, and when possible a prototype, of an improved product. Through various conversations with the client, it is understood that providing a completely new conceptual iteration would not fulfill the client's expectations. Thus, to provide valuable progress, different areas of improvement are considered and addressed: Human Range of Motion, Virtual Immersion and MoCap, Dead-man grip, Sensor Box, Power management, Industrial design and Manufacturing, Prototyping, and Innovation management.

In this project, interdisciplinary knowledge will be utilized and integrated to achieve a product concept. Furthermore, theoretical knowledge will be combined with practical hands-on experience and literature analysis on social, scientific, and ethical issues. Lastly, future scope and a road map are addressed to guarantee the project's continuity. The report gathers all the aforementioned aspects, guiding the reader through the project process.
                  </p>
              </details>
          </p>  
     </td>
  </tr> 


 <tr>
       <td width="14%"  valign="top">
            <img src="/images/projects/mindswitch.png" alt="mindswitch" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>MindSwitch</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://www.youtube.com/watch?v=Sq5F-VKy3Hg&t=72s&ab_channel=Prithvish">Video</a> | <a href="">Poster</a> Poster</summary>            
                  <p class="message">
                  </p>
              </details>
          </p>  
     </td>
  </tr> 

   <tr>
       <td width="14%"  valign="top">
            <img src="/images/projects/dmd4dmd.png" alt="dmd4dmd" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>DMD4DMD</paper>
              <br>  
              <b>Prithvish V N </b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://sites.psu.edu/resnasdc/2016/11/19/dmd4dmd-dystrophy-monitoring-device-for-duchenne-muscular-dystrophy-vit-university-chennai-campus/">Paper</a>  |<a href="https://www.youtube.com/watch?v=9QYNSk4zlRM&ab_channel=Prithvish">Video</a> </summary>            
                  <p class="message">
                  Duchenne Muscular Dystrophy is one of the rare diseases for which there has been no cure till date. This disease affects 1 in 3500 male children and the life expectancy of the patient is about 15-20 years. Our device, DMD4DMD, helps practitioners and researchers monitor and analyze the progressiveness of disease. The design aims at minimizing the hardware such that the device is light in weight, wireless and wearable.  One of the main significance of this device is to create a global repository where any physician around the globe can access data and analyze the condition of patients.  Our device expands the area of research of a rare disease whose symptoms are hard to diagnose at early stage.
                  </p>
              </details>
          </p>  
     </td>
  </tr> 

   <tr>
       <td width="14%"  valign="top">
            <img src="/images/projects/badminton.png" alt="DIA" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper></paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
            Twelfth (ICLR 2024)
              <details>
                <summary>Abstract  | <a href="">Report</a> | <a href="https://www.youtube.com/watch?v=vlZIPXOWXLo&feature=youtu.be&ab_channel=Technocrats"</a> Video</summary>            
                  <p class="message">
                  </p>
              </details>
          </p>  
     </td>
  </tr> 
</table>
