---
layout: post
title: Novel signal processing to visualize plasma waves in a tokamak
description: For the first time, core magnetohydrodynamic activity was recorded with a high speed visible camera. 

image: assets/images/MHD_1.PNG
---

### Motivation
Fusion energy is a possible solution to climate change because in theory fusion can provide a clean, safe, and sustainable source of energy. The leading device for magnetically confined fusion is a doughnut shaped plasma container called a [tokamak](https://en.wikipedia.org/wiki/Tokamak). The name of the game in fusion is **confinement**, meaning that fusion fuel is packed sufficiently close together for a long time and with sufficient heat to produce enough fusion reactions to make the whole endeavor worthwhile. That is, you want to get more energy out than you put into the plasma. Stars achieve fusion because their strong gravitational field, and here on Earth we use magnetic fields for plasma confinement.

<center>
<figure>
  <img src="{{site.url}}/assets/images/ITER.jpg" alt="ITER tokamak" height="38%" width = "38%"/>
  <figcaption>
  	<em>
  		Figure 1 - A tokamak is a doughnut shaped plasma confinement device for fusion energy. Can you find the little man? 
  	</em>
  </figcaption>
</figure>
</center>
<p>&nbsp;</p>


Plasma waves and instabilities are important areas of fusion energy research because they can lower the plasma pressure and reduce fusion performance. I have achieved the first-ever fast camera images of core plasma mode structure and dynamics by detecting visible plasma emission in the top U.S. fusion facility known as the DIII-D tokamak. The ability to visualize the core plasma using fast cameras allows the study of waves and instabilities in unprecedented detail.



<center>
<figure>
  <img src="{{site.url}}/assets/images/MHD_5.PNG" alt="Camera view" height="20%" width = "20%"/>
  <figcaption>
  	<em>
  		Figure 2 - Cross section of the DIII-D tokamak with a typical field of view from the fast camera, which can take tens of thousands of images every second. The dashed lines show closed surfaces of constant magnetic flux, with the highest magnetic field (2 Tesla, or about 40,000x the Earth's magnetic field) near the center.
  	</em>
  </figcaption>
</figure>
</center>
<p>&nbsp;</p>




### Tearing modes
Figure 3 shows the structure of a tearing mode, which is caused by a perturbation of either the plasma pressure or the helical electric current flowing in a tokamak. When this pertubation is located at so-called rational magnetic flux surfaces, i.e., where the helical magnetic field lines wrap around on themselves, magnetic fields can tear apart and reconnect to form a magnetic island. These structures degrade the performance of the tokamak, which is intended to have simple nested magnetic flux surfaces (as seen in Figure 2).


<center>
<figure>
  <img src="{{site.url}}/assets/images/MHD_2_TM.PNG" alt="Tearing mode" height="40%" width = "40%"/>
  <figcaption>
  	<em>Figure 3 - A novel signal processing technique is used to create these images. The time sequence from each camera pixel is Fourier transformed and then filtered (only certain frequencies are retained). The resulting images show (a) the Fourier amplitude, (b) phase, and (c) a snapshot of the mode structure. The fundamental rotation frequency of the magnetic islands is retained in (a) - (c) which shows poloidal mode structure of m = 2, and the first harmonic frequency is retained in (d) - (f) showing m = 4 structure.</em>
  </figcaption>
</figure>
</center>
<p>&nbsp;</p>




<center>
<figure>
  <img src="{{site.url}}/assets/images/MHD_3_TM.PNG" alt="Synthetic camera" height="30%" width = "30%"/>
  <figcaption>
  	<em>
  		Figure 4 - A model of plasma light emission from tearing modes is used to create synthetic camera images (shown in the left column), which are compared to real camera data (right hand column).
  	</em>
  </figcaption>
</figure>
</center>
<p>&nbsp;</p>



### Sawtooth instability
Another plasma instability which I had the privilege of imaging for the first time ever is called a sawtooth crash. The sawtooth instability forms when the plasma current is peaked near the magnetic axis, causing plasma from the core to rapidly mix with the cooler outer regions. This is a bad thing, because the game in fusion is to keep a dense plasma extremely hot for as long as possible in order to produce a lot of fusion reactions. The mixing is very fast (about 100 microseconds). After the crash, the central temperature gradually rises as the current profile and fast ion population evolve, and the process repeats. The exact nature of the magnetic reconnection that occurs during the sawtooth crash has eluded a complete physics explanation, and fast imaging of these events may provide new insights through detailed comparison to theory. Magnetic reconnection is also a hot topic in the astrophysics community, because reconnection occurs during solar flares and coronal mass ejections. These magnetic storms can even [interfere with power grids on Earth](https://www.sciencealert.com/here-s-what-would-happen-if-solar-storm-wiped-out-technology-geomagnetic-carrington-event-coronal-mass-ejection)!



<center>
<figure>
  <img src="{{site.url}}/assets/images/MHD_4.PNG" alt="Sawtooth crash" height="40%" width = "40%"/>
  <figcaption>
  	<em>
  		Figure 5 - (a) The electron temperature as a funcion of time during a sawtooth crash. The vertical lines show the times of the images. (b) Snapshots of the Fourier-filtered (15 kHz) component of visible light from the plasma.
  	</em>
  </figcaption>
</figure>
</center>
<p>&nbsp;</p>


Check out my publications about this topic <a href = " {{ site.url }}/assets/publications/31.pdf "> here </a>, 
<a href = " {{ site.url }}/assets/publications/19.pdf "> here </a>, and <a href = " {{ site.url }}/assets/publications/16.pdf "> here </a>.