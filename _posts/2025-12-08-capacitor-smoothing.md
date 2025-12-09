---
layout: post
title: Capacitor smoothing
author: Harry
tag: Electronics
---

Circuit made using the [Falstad](https://www.falstad.com/circuit/) circuit simulator.
<img src="{{ site.baseurl }}/assets/images/capacitor_smoothing.png" alt="Capacitor Smoothing">
Circuit file for testing the circuit yourself:
<a href="{{ site.baseurl }}/download/capacitor_smoothing.txt" download>
  capacitor_smoothing.txt
</a>
<br/>
<br/>

This is a simple first circuit that gradually increases an LED's brightness when
the switch is held down and it dims the LED when the switch is open.
<br/>
<br/>
Increasing the resistor value will result in the LED taking more time to brighten.
<br/>
<br/>
You can increase the simulation speed from the website's interface to view this effect happening faster.
<br/>
<br/>
This is the circuit on a breadboard. 
<img src="{{ site.baseurl }}/assets/images/cap_smoothing_breadboard.jpg" alt="Capacitor Smoothing">
To make this yourself you will need:
- A breadboard;
- An electrolitic capacitor rated 100uF, would work with other ratings too;
- A 1Kohm resistor, can also use lower/higher rated resistors to study the effects;
- Any kind of switch;
- A 9V battery;
- Additional wires, but the circuit can be made with no wires;

Capacitor smoothing in action:
<video width="100%" controls muted>
  <source src="{{ site.baseurl }}/assets/videos/cap_smoothing_vid.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>