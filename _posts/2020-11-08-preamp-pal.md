---
layout: post
title: "2. Preamplifier with RIAA Equalization"
subtitle: Preamplifier with RIAA Equalization for turntables
cover-img: /assets/img/banner5.jpg
thumbnail-img: /assets/img/PreampRIAA.png
share-img: /assets/img/PreampRIAA.png
gh-repo: rcarapinha/PreampPAL
gh-badge: [star, fork, follow]
tags: [turntable, pcb, ltspice, eagle]
comments: false
---

The goal was to perform a low-noise pre-amplifier that amplifies the needle signal from a turntable to a line level signal. To accomplish this we started by understanding what was a preamplifier for a record player, namely, what was a preamplifier with reverse RIAA equalization that would amplify the needle signal to a line level signal.

Having said this, we started the search for a preamplifier that corresponded to our needs, i.e., a preamplifier that applied what was described above and low noise (because the values received by the needle are very low).

A range of preamplifiers were chosen and then the simulation phase started using the LTSpice program.

Several simulations in LTSpice in terms of noise and equalization were performed in order to choose the best pre-amplifier. At the end of this phase we started to develop the circuit.

<center>
	<img src="https://raw.githubusercontent.com/RCarapinha/PreampPAL/master/Simulation/1.JPG">
</center>

<br> The first test to be performed was to make sure that the voltage regulator (low noise) correctly converted the value from 5V to 3.3V, and this test was successful. The second test was to verify the amplification and RIAA equalization. For this, a weak signal was applied to the input and we compared the output values obtained with the theoretical output values.

<center>
	<img src="https://raw.githubusercontent.com/RCarapinha/PreampPAL/master/Preamp%20Board/breadboard.png">
</center>

<br> After we carried out the tests and validated the operation of the circuit, the next step of the team was to develop the PCB (in EAGLE software) so that we could finish the work.

<center>
	<img src="https://raw.githubusercontent.com/RCarapinha/PreampPAL/master/Preamp%20Board/pcb.png">
</center>

<br> Once the PCB has been designed, we start to build the board and assemble the components on it, something that must be done with great care to avoid errors or noise. Finally, we tried to isolate the whole board, for a better functioning.

<center>
	<img src="https://raw.githubusercontent.com/RCarapinha/PreampPAL/master/Preamp%20Board/breadboard.png">
</center>

The following frameworks were used:
- LTSpice,
- EAGLE.