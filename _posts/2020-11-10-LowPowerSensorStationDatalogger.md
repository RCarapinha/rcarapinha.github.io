---
title: 
---

---
layout: post
title: "4. Low Power Sensor Station Datalogger"
subtitle: Robotic Arm with Arduino, Bluetooth and Android
cover-img: /assets/img/RobotArm.png
thumbnail-img: /assets/img/RobotArm.png
share-img: /assets/img/RobotArm.png
gh-repo: rcarapinha/RobotArm
gh-badge: [star, fork, follow]
tags: [arduino, bluetooth, android]
comments: false
---

This project is based on an ATmega328 processor and the goal is to last the most time possible with a 3.3V battery.
The component of storing and analyzing the data is just to check that it's possible to have a proper function of the processor even when it spends the most part of the time sleeping.

This project was only possible due to the article available <a href="https://www.gammon.com.au/power" style="color:#fff">here</a>. Here's it's possible to see different methods to achieve low-power in the ATmega328 processor, such as, decreasing frequency and voltage, disabling the ADC, the brownout detection, etc.

The main objective of this project was the Low Power Mode, Data log (save to an SD card values of temp., humidity, light, etc.) and a Matlab Interactive Interface to read and analyze the data.
It must last a reasonable time with the battery, store correctly the values and have a proper analysis program.

<center>
	<img src="/assets/images/Breadboard.png" width="500">
</center>

<br> Even with low-power we achieve the same output as it's possible to see.

<center>
	<img src="/assets/images/Matlab.png" width="500">
</center>

<br> The following frameworks were used:
<ul>
  <li>Arduino,</li>
  <li>MATLAB.</li>
</ul>

The source code is available <a href="https://github.com/RCarapinha/LowPowerSensorStationDatalogger" style="color:#fff">here</a>.
