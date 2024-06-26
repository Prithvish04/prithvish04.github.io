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
                <summary>Abstract  | <a href="https://github.com/Prithvish04/reconfigurable_project">Code & Report</a>  </summary>            
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
                <summary>Abstract  | <a href="https://github.com/Prithvish04/Processor_Design_MIPS_improvements">Code & Report</a> </summary>
                  <p class="message">
                  This project aims to lay out the changes made to a simple MIPS architecture processor in order to improve severalperformance metrics of it such as speed, energy use and power consumption, as well as area. For this reportin particular the decreasing energy consumption while maintaining decent performance was considered aboveall. To that end, three major parts of the original processor were modified. Those were the cache hierarchy,the adder module for the alu and also the multiplier unit. In this report through design space exploration thebest cache configuration was found, resulting in about 3.2 Joules saved and 2.8 million cycles less. Finally, afterdoing research, the best options for the other two changes were found. Where after a radix-4 multiplier anda prefix adder were implemented. A final processor capable of running the benchmarks in 4948 million cycleswith only 7.59 Joules was achieved.
                  </p>
              </details>
          </p>  
     </td>
  </tr> 
 
   <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/deeporchards.png" alt="deeporchards" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Deep Orchards - Reproducibility project</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/Deep-orchards">Code & blog</a>  </summary>            
                <p class="message">
                Terms like Deep learning and machine learning have been quite popular these days. There have been several advancements in the field over the last couple of years. Having seen several fields slowly adapting techniques to solve problems via deep learning and machine learning encouraged encouraged us to take up deep learning courses in our Masters. While courses give you a basic understanding on a subject, Projects have always been an interesting way of learning new concepts hence we took up a challenging project to integrate the Deep Orchards dataset with the Faster RCNN network and reproduce the research paper. The work takes you through the very basic steps one should follow if you are a newbie in deep learning.
                </p>
              </details>
          </p>  
     </td>
  </tr> 




     <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/.png" alt="kitchen" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper></paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/kitchen_robot">Code & blog</a>  </summary>            
                <p class="message">



                </p>
              </details>
          </p>  
     </td>
  </tr> 


      <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/system_validation.png" alt="system_validation" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Starliner mission model in mCRL2</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/">Code & blog</a>  </summary>            
                <p class="message">
                This system validation project will focus solely on the launch segment of the Starliner Mission. The launch starts on the ground and terminates when the Service and Crew Modules (SCM) are detached from the Orbital Module (OM). The main events as listed below will be modelled in mCRL2 using four independent controllers running in parallel. As further described in section 2, these consist of a Flight Controller (FC), Booster Module Controller (BMC), Launch Module Controller (LMC), and Orbital Module Controller (OMC)
                </p>
              </details>
          </p>  
     </td>
  </tr> 


        <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/rtems.png" alt="rtems" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>RTEMS - RTOS Survey</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/">Code & blog</a>  </summary>            
                <p class="message">



                </p>
              </details>
          </p>  
     </td>
  </tr> 

    <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/acs_1.png" alt="rtems" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Acceleration with SSE/AVX/AVX2 OpenMP, OpenCL</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/">Code & blog</a>  </summary>            
                <p class="message">
                This project is focused on the analysis of various computational techniques by implementing matrix multiplication. Our goal is to accelerate and optimize both single-precision and double precision matrix multiplication by the use of Intel SSE/AVX/AVX2, OpenMP and OpenCL on multi-core processor systems. We state our observations of the performance of each implementation and analyze why and when which imple-mentation works better. We benchmarked the implementations with that of a native matrix multiplication wherein no optimizations have been applied. We then conclude with a brief discussion of the current trend on how each of these paradigms are being used currently. 
                </p>
              </details>
          </p>  
     </td>
  </tr> 

      <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/acs_2.png" alt="rtems" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Accelerating image processing algorithms with CUDA</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/">Code & blog</a>  </summary>            
                <p class="message">
                This report is focused on the implementation and analysis of the optimization of a basic image processing algorithm using NVIDIA CUDA toolkit. CUDA is a parallel computing platform and programming model developed by NVIDIA for general computing on graphical processing units (GPUs). With CUDA, it is possible to dramatically speed up computing applications by harnessing the power of GPUs. In our case, the image processing algorithm consists of 4 stages namely histogram calculation, contrast enhancement, ripple effect and Gaussian blurring. We provide the optimized algorithm and compare the performance of the with that of the serial execution.
                </p>
              </details>
          </p>  
     </td>
  </tr> 

       <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/acs_2.png" alt="rtems" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Acceleration of a Convolution Neural Network</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/">Code & blog</a>  </summary>            
                <p class="message">
                This report is focused on the implementation and analysis of the optimization of a basic CNN classification algorithm. CUDA is a parallel computing platform and programming model developed by NVIDIA for general computing on graphical processing units (GPUs). With CUDA, it is possible to dramatically speed up computing applications by harnessing the power of GPUs. We provide the optimized algorithm and com-pare the performance of the same with that of the base- line serial implementation. We also try to use various other paradigms whenever possible to get the maxi-mum performance out of the algorithm. 
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
                <summary>Abstract  | <a href="https://www.youtube.com/watch?v=Sq5F-VKy3Hg&t=72s&ab_channel=Prithvish">Video</a> | <a href="https://github.com/Prithvish04/NIYANTRA_mindswitch">Repository</a> <a href ="https://github.com/Prithvish04/NIYANTRA_mindswitch/blob/main/docs/mindswitch_poster_final.pdf"> Poster</a> <a href="">Report </a></summary>            
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
              <paper>Team Technocrats - Badminton Playing Robots </paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
              ROBOCON 2015 ASIA PACIFIC
                <summary>Abstract  | <a href="">Repository</a> | <a href="https://www.youtube.com/watch?v=vlZIPXOWXLo&feature=youtu.be&ab_channel=Technocrats">Video </a> | <a href="https://technocratsrobotics.in/">Website </a>   </summary>            
                  <p class="message">
                  ROBOCON is an Asia-Pacific robotics competition held every year with different problem statements. The problem statements are carefully curated to encourage design innovations in the field of robotics. The problem statement for the year 2015 was to make 2 robots that will play a doubles badminton match with the other team’s robots. The choice of fully automated vs manual robots was provided by the organisers. 
                  </p>
              </details>
          </p>  
     </td>
  </tr> 

   <tr>
       <td width="14%"  valign="top">
            <img src="/images/projects/person_id.png" alt="mindswitch" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Multi-Model Person Identification System</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="">Repository</a> | <a href="">Report</a> Poster</summary>            
                  <p class="message">
                In this project, we present an audio-visual feature-level fusion for person identification system using a combination of acoustic features, fingerprint images and 2D face images. Person identification is of paramount importance in security, surveillance, human computer interfaces, and smart spaces. There are numerous instances where a single feature, however, sometimes fails to be exact enough for identification. Also, another disadvantage of using only one feature is that the chosen feature is not always readable. Thus, a multimodal approach using three different modalities - face, voice and fingerprint - takes care of all such instances and achieves greater accuracy than single feature systems. The speaker verification is done by extracting Mel Frequency Cepstral Coefficients followed by Support Vector Machine. The facial recognition is done using Local Binary Pattern histogram face recognizer after performing Harr cascade for face detection. The fingerprint verification is done using binarization on a grayscale image, followed by skeletonization and then the minutiae points are found using Harris corner detector. All the three above approaches are implemented on hardware using BeagleBone Black along with audio microphone and USB cameras as sensory modules. The various sensory modalities, speech, fingerprint and faces, are processed both individually and jointly and it has been observed that the performance of the multimodal approach results in improved performance in the identification of the participants. Our system achieves around 90% recognition and verification rates on natural real-time input with 10 registered clients.
                </p>
              </details>
          </p>  
     </td>
  </tr> 

       <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/study_i2c_msp430.png" alt="kitchen" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Study of I2C communicaiton protocol using MSP430 and Beagle Bone Black</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/study_I2C_msp430/blob/main/Advanced_microcontroller_report.pdf">Report</a>  </summary>            
                <p class="message">
                I²C (Inter-Integrated Circuit), pronounced I-squared-C, is a multi-master, multi-slave single-ended, serial computer bus invented by Philips Semiconductor (now NXP Semiconductors). It is typically used for attaching lower-speed peripheral ICs to processors and microcontrollers in short-distance, intra-board communication. Alternatively, I²C is spelled I2C (pronounced I-two-C) or IIC (pronounced I-I-C). BBB, MSP430 and MPU-6050 having the same operating voltage have been selected as the test and study purpose. In our test BBB is configured as the Master and MPU and MSP being the slaves. Register for MSP430 I2c communication and I2Ctools for BBB will be studied and CCS and Putty will be the Software tools used. The Coding on BBB is done in C. Various modes of I2C were tested and MPU was studied via the help of datasheet. The Acceleration values on MPU and temperature values on MSP was acquired on BBB and displayed.
                </p>
              </details>
          </p>  
     </td>
  </tr> 


       <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/.png" alt="kitchen" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper></paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="">Report</a>  </summary>            
                <p class="message">


                </p>
              </details>
          </p>  
     </td>
  </tr> 


       <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/vending.png" alt="vending" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Vending Machine</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/vending_machine">Report</a>  </summary>            
                <p class="message">
                The project is a replication of vending machines used in Metro localities such as Delhi, Mumbai, Bangalore and other cities abroad. Vending machine is an automated machine that dispenses products in exchange of money that is put into the system. In other words it’s a money operated automated machine for selling merchandise. The task comprises of three stages –finite state machine, followed by sensing hardware and then finally product dispensing mechanism. The project is majorly based on the finite state machine to maneuver the system. The system senses two currency notes (Rs.10 and Rs.20) using SIFT algorithm. The system is efficient in dispensing products more like wafers and chocolates. As per the design the machine will dispense a product only for amount exactly Rs.30. The machine additionally consists of a cancelling mechanism which cancels the order and returns the amount back to the customer.
                </p>
              </details>
          </p>  
     </td>
  </tr> 
        <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/gesture.png" alt="gesture" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Gesture based locking system</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/gesture_lock">Report</a>  </summary>            
                <p class="message">
                This project aims to design a revolutionary security system that shall change the present day scenario of opening door locks. A mere gesture of your hand shall unlock the door on which the system is installed. The basic prototype will consist of a small cubical box with laser and LDR array. When the proper Finger gesture is produced in the box, a comparison is made based on a previous pattern recorded. A Stack and polling based concept of the microcontroller/microprocessor will come into picture while interfacing the Laser-LDR system. On circumstantial failure of the above Sub-System after a particular amount of trials, the locking system starts its own access point network through which the owner can connect via his phone. Further a custom made app will be needed to unlock the lock. In this process the lock system will start its own server and the owner’s phone shall act as client. On the door opening request of the client the server will open and close the door when properly authenticated by the correct password. The level of security in such a system is doubled in the second subsystem with a 2 level authentication by the WEP encryption based WIFI security and the App Passkey security
                </p>
              </details>
          </p>  
     </td>
  </tr> 




     <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/horn_antenna.png" alt="kitchen" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Design for a horn Antenna</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/HFSS_projects/blob/main/horn_antenna_report.pdf">Report</a>  </summary>            
                <p class="message">
                Horn antennas are extremely popular in the microwave region. An aperture antenna contains some sort of opening through which electromagnetic waves are transmitted or received. One of the examples of aperture antenna is horns. The analysis of aperture antennas is typically quite different than the analysis of wire antennas. So in this project, the team decided to simulate a pyramidal horn antenna in HFSS 13, since pyramidal antennas are widely used for communication purpose. The resonating frequency was fixed at 10GHz and the 3D Polar plot, rectangular plot for impedance of horn antenna, Gain v/s Frequency plot, directivity plot and antenna parameters were obtained for a practical design of pyramidal horn antenna.
                </p>
              </details>
          </p>  
     </td>
  </tr> 

       <tr>
    <td width="14%"  valign="top">
        <img src="/images/projects/band_pass_filter_hfss.png" alt="kitchen" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Band-pass filter design for microwave frequency using HFSS</paper>
              <br>  
              <b>Prithvish V N</b>,    
            <br>
              <details>
                <summary>Abstract  | <a href="https://github.com/Prithvish04/HFSS_projects/blob/main/13BEC1100_1138_1113_FINAL_REPORT.pdf">Report</a>  </summary>            
                <p class="message">
                At the receiver side there is a requirement to filter out the noises and pass only the desired signal frequency for processing. Hence, a Band Pass Filter (BPF) is required for the same. In the present project the designing of a compact microwave parallel edge coupled line BPF has been discussed and implemented. The BPF consists of a 4-parallel coupled line pairs designed for a Chebyshev response at a center frequency of 2.48 GHz with a fractional bandwidth of 10%. The filter has been implemented using FR4 substrate of dielectric constant 4.2. The physical parameters of the parallel coupled line filter sections have been simulated using the HFSS software to provide the closest values of the band pass filter prototype values.
                </p>
              </details>
          </p>  
     </td>
  </tr> 

</table>


