---
layout: single
title: \[KAIST\] Capcitance based Pedometer
permalink: /docs/otherworks/otherworks-kaist-pedometer
author_profile: false
classes: wide
---

[KAIST] Capcitance based Pedometer

<figure style="width: 400px" class="align-left">
  <a href="/assets/images/kaist-pedometer/implementation-square.png"><img src="/assets/images/kaist-pedometer/implementation-square.png"></a>
  <figcaption>Test caption TTBot</figcaption>
</figure> 


Development of two prototypes of built-in pedometers. One prototype was measuring foot pressure by monitoring the capacitance between integrated metal plates in the insole. When the pressure was applied, the distance between the plates changed which causes the change in the capacitance. We measured this difference of capacitance by using Capacitance-to-Digital-Converter(CDC). The other prototype was the pedometer to measure the proximity between two feet. One shoes had an oscillator pad, and the other shoes had a detector pad to measure the amplitude of the oscillated signal. As the distance between two pads changed, the amplitude of the oscillated signal is changed, and we can use this signal as to roughly estimate when the pads are crossing each other.

 

This project is mentored by Dr. SeongHwan Cho at KAIST.

 

Team Member : Sujin Park (EE senior at KAIST)

{% include video id="193679727" provider="vimeo" %}

{% include video id="193679637" provider="vimeo" %}