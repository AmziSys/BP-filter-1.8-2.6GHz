# BP-filter-1.8-2.6GHz

------------------------ BP filter @ 1.8/2.6GHz ------------------------

* In this project, a dual-band bandpass filter based on only one dual-mode Stepped Impedance Resonator (SIR)is designed, and it operates simultaneously at 1.8 GHz and 2.6 GHz.

* Design;
	- Study/Design of the main filter element ---> the resonator: The SIR resonator is chosen because of its compactness and significant design freedom in passband control.
	- Bandpass filter Design ---> based on a single SIR with an I/O port that consists of a feeding line (50 Ω) and a parallel coupling arm (energy coupling type)
	
* Simulation: 
	the simulated frequency response of the proposed filter shows good performances in terms of gain and losses, respectively, -0.41dB, -22dB at 1.8GHz, and -0.55dB, -21.5dB at 2.62GHz. 

* Measurement: 
	The measured result shows good agreement with the simulated ones, in bandwidth and rejection level (high rejection band level. However, the gain and losses are shifted compared to those simulated, this could be due to the precision of the fabrication machine. The second reason might be a small difference in the characteristics of the substrate between the simulated one and the one used in fabrication.

The manufactured filter has a compact size (19x14 mm²), which is suitable for 4th LTE/multiband mobile phone communication systems.

* The design was made on CST microwave-studio and HFSS.
