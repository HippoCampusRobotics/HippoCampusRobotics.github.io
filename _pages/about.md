---
title: "About"
permalink: /pages/about/
layout: splash
excerpt: "About HippoC"
sitemap: false
feature_row:
  - image_path: https://www.tuhh.de/t3resources/mum/_processed_/csm_2014-12-05_10.28.15_nocable_small_34d2a69318.jpg
    excerpt: "Working early prototype of HippoCampus."   
  - image_path: AUV_CAD.jpg
    excerpt: "Next generation conceptual CAD rendering of HippoCampus."
  - image_path: AUV.JPG
    excerpt: "Current version of HippoCampus." 
---
<div style="margin-left:10%; margin-right:10%;">
The world's oceans have been a crucial part for life on earth in the past and present, but will also determine our future. They include the least explored areas on earth due to the high cost and the risks involved in offshore and deep-sea activities. Recent technological advances in underwater robotics promise to open up groundbreaking possibilities in offshore areas, such as oceanographic research, offshore wind and deep sea mining. Autonomous underwater vehicles (AUVs) are becoming increasingly important and will play a prominent role in the future. Today mostly single, highly specialized and very expensive vehicles are deployed. They usually have a low degree of autonomy and need a large vessel to be deployed. In order to optimize the use of these scarce resources, the next generation of autonomous underwater vehicles has to be able to evaluate mission performance and coordinate itself with other vehicles working on the same or similar task.
</div>

<h1>Motivation</h1>
The world's oceans have been a crucial part for life on earth in the past and present, but will also determine our future. They include the least explored areas on earth due to the high cost and the risks involved in offshore and deep-sea activities. Recent technological advances in underwater robotics promise to open up groundbreaking possibilities in offshore areas, such as oceanographic research, offshore wind and deep sea mining. Autonomous underwater vehicles (AUVs) are becoming increasingly important and will play a prominent role in the future. Today mostly single, highly specialized and very expensive vehicles are deployed. They usually have a low degree of autonomy and need a large vessel to be deployed. In order to optimize the use of these scarce resources, the next generation of autonomous underwater vehicles has to be able to evaluate mission performance and coordinate itself with other vehicles working on the same or similar task.

<div style="width:80%;margin:auto;">{% include feature_row %}</div>

<h1>Project Description</h1>
We develop an AUV system with a computational fluid dynamics (CFD) simulation in the loop. This allows the modeling of realistic environmental dynamics by the simulation of the flow field and an estimation of sinks, sources (of heat, pollution, etc) and boundary conditions. Also, the results from the fluid dynamics simulation are fed back into the path planner for the AUVs. Depending on the mission objectives, regions with a high likelihood for sources can be of higher or lower interest as regions with a high field variable variance. Task allocation and consensus algorithms decide how the team of vehicles navigates within the field to satisfy both, robustness and a fast mission execution.


<h1>Vehicle Hardware</h1>
The current underwater vehicle setup represents a very flexible and robust control platform. We use a <a href="https://pixhawk.org/modules/pixhawk" target="_blank">Pixhawk</a> board with a 168 MHz Cortex M4F CPU (256 KB RAM, 2 MB Flash) and onboard sensors (3D ACC / Gyro / MAG / Baro). PX4 is an independent, open-source, open-hardware project (BSD licensed) for mobile robotics applications. The PX4 platform runs <a href="https://en.wikipedia.org/wiki/NuttX" target="_blank">NuttX</a>, a small footprint real-time operating system (RTOS), which provides a POSIX-style environment. The PX4 middleware runs on top of the operating system and provides device drivers and a <a href="https://en.wikipedia.org/wiki/Object_request_broker" target="_blank">micro object request broker (uORB)</a> for asynchronous communication. Our HippoCampus control stack is a custom, BSD licensed underwater vehicle control stack, providing remote controlled and fully autonomous operations for our underwater vehicle hardware.

<a href="https://github.com/EugenSol/FirmwareBeta" class="btn btn--warning" target="_blank">Our GitHub repository</a> 

The vehicle is easy to assemble and is made of off-the-shelf components, 3D printed parts and printed circuit boards. The quad-rotor layout makes the vehicle extremely agile and suitable for hydrobatic maneuvers. 
