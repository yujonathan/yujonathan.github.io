---
layout: post
title: Predicting the impact of hot plasma on materials. Or, how to not break a fusion reactor.
description: You might think that two heat pulses with the same total energy, same pulse width, and same peak power, would affect materials in the exact same way. Well, it turns out to be more subtle than that. 

image: assets/images/75_1.PNG
---


### The question
Plasma instabilities in a fusion power plant will heat material surfaces up to their melting point and beyond, leading to potential mechanical failure and radical changes to thermomechanical properties. Thermal testing of materials is usually done off-line using lasers or electron beams to simulate plasma instabilities, by matching certain parameters such as energy density and pulse width. However, these heat sources usually do not match the temporal (time) shape of the actual plasma instabilities, which caused me to question how the temporal shape of the heat pulse affects the extent of material damage and peak surface temperature reached during the pulse. Some people thought I was wasting my time because after all, doesn't conservation of energy say that the energy per pulse is what matters in terms of material heating?


![Tungsten laser damage]({{ site.url | absolute_path}}/assets/images/75_3.PNG){:height="75%" width="75%"}
 <figcaption>
Figure 1 - Microsope images of tungsten after 100 laser pulses, showing the striking differences in surface roughening and melting due to various temporal pulse shapes. Images in each row show laser spots exposed to the same absorbed energy density, and different pulse shapes are shown in each column. The peak surface temperature reached during a heating pulse and the root-mean-squared surface roughness are shown at the top of each image.
 </figcaption>
<p>&nbsp;</p>


![Pulse shape]({{ site.url | absolute_path}}/assets/images/75_1.PNG){:height="50%" width="50%"}
 <figcaption>
 	Figure 2 - (a) Various temporal pulse shapes from a laser are used to heat material, and (b) shows the surface temperature from each type of heat pulse. The peak surface temperatures are significantly different from each other, even though all the heat pulses have the same total energy.
 </figcaption>
<p>&nbsp;</p>


![Pulse shape simulation]({{ site.url | absolute_path}}/assets/images/77_1b.PNG){:height="50%" width="50%"}
 <figcaption>
 	Figure 3 - (a) Finite element simulations of heat pulses from various temporal pulse shapes, and (b) the simulated surface temperature from each type of pulse.
 </figcaption>
<p>&nbsp;</p>


### The results
Actually, the temporal shape **does** have a significant effect due to the diffusive nature of heat flow into the material.Pulses with the same peak power, same energy per pulse, and same pulse width can cause different peak temperatures! For Figures 1 and 2, I programmed a laser with different temporal pulse shapes and fired the laser at tungsten, a leading material for future fusion reactors, in order to simulate heating from plasma instabilities. In Figure 3, the surface temperature calculated from computer simulations of heating diffusing into the material are shown. These data show that the maximum surface temperature is not the same for the pulses, despite the fact that all the pulses have the same power density and pulse widths. In fact, the difference in peak surface temperature is up to 40%, which may mean the difference between successful operation and possible catastrophic failure of the material. The surface temperatures were measured optically using a high speed pyrometer that I designed and built. 

### Who cares?
This work is important because predicting the impact of powerful heat pulses from a fusion plasma is critical to the success and survivability of a fusion power facility. It turns out that plasma instabilites typically have a unique temporal shape, and if the shape is not properly considered during material testing and numerical modeling, all bets are off in terms of predicting what will happen in an actual fusion reactor. The biggest risk is cracking of the wall material, which can lead to a coolant leak, major damage to the reactor vessel, and prolonged reactor shutoff for repairs.


![Temperature rise]({{ site.url | absolute_path}}/assets/images/75_2.PNG){:height="50%" width="50%"}
 <figcaption>
 	Figure 4 - The peak surface temperature rise for different shaped triangular heating pulses is shown as a function of the pulse rise time Tau_r (normalized to the pulse width Tau_s of a square pulse with the same energy and same peak power). The peak surface temperature strongly depends on the shape of the heating pulse. Data points are compared to theory (solid line) and finite element analysis modeling (red circles), and there is general agreement within the uncertainty of the measurements.
 </figcaption>


