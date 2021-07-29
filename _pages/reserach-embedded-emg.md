---
layout: single
title: Advanced Electromyography for Human Biomechanics and Bionics Research
permalink: /docs/research/research-embedded-emg
author_profile: false
classes: wide

gallery_emgabstract:
  - url:  /assets/images/research-emg/emg-socket-square.png
    image_path: /assets/images/research-emg/emg-socket-square.png

gallery_emg_prototype:
  - url:  /assets/images/research-emg/system-diagram.PNG
    image_path: /assets/images/research-emg/system-diagram.PNG

  - url:  /assets/images/research-emg/hw_summary.jpg
    image_path: /assets/images/research-emg/hw_summary.jpg
    # title: "EMG Board Summary"

gallery_emg_designconcept:
  - url:  /assets/images/research-emg/afe-architecture.PNG
    image_path: /assets/images/research-emg/afe-architecture.PNG

  - url:  /assets/images/research-emg/os-schedule-scheme.PNG
    image_path: /assets/images/research-emg/os-schedule-scheme.PNG

  - url:  /assets/images/research-emg/memory-buffering.PNG
    image_path: /assets/images/research-emg/memory-buffering.PNG

gallery_emg_verification:
  - url:  /assets/images/research-emg/result_time_wet2.png
    image_path: /assets/images/research-emg/result_time_wet2.png

  - url:  /assets/images/research-emg/reset_psd_wet.png
    image_path: /assets/images/research-emg/result_psd_wet.png

  - url:  /assets/images/research-emg/noise_psd_wet.png
    image_path: /assets/images/research-emg/noise_psd_wet.png

gallery_SLIP_demo:
  - url:  /assets/images/research-emg/fig8c_electrode-attached.PNG
    image_path: /assets/images/research-emg/fig8c_electrode-attached.PNG

  - url:  /assets/images/research-emg/fig8e_electrode-liner1.PNG
    image_path: /assets/images/research-emg/fig8e_electrode-liner1.PNG

  - url:  /assets/images/research-emg/fig14a_comfort-slip-electrode.jpg
    image_path: /assets/images/research-emg/fig14a_comfort-slip-electrode.jpg

gallery_US_demo:
  - url:  /assets/images/research-emg/exp-setup-human2.png
    image_path: /assets/images/research-emg/exp-setup-human2.png

  - url:  /assets/images/research-emg/us-emg-probe.PNG
    image_path: /assets/images/research-emg/us-emg-probe.PNG

  # - url:  /assets/images/research-emg/result-TA-we-EMG.png
  #   image_path: /assets/images/research-emg/result-TA-we-EMG.png

gallery_chf_alg:
  - url:  /assets/images/research-emg/chf-alg1.PNG
    image_path: /assets/images/research-emg/chf-alg1.PNG

  - url:  /assets/images/research-emg/chf-alg2.PNG
    image_path: /assets/images/research-emg/chf-alg2.PNG
  - url:  /assets/images/research-emg/chf-alg3.PNG
    image_path: /assets/images/research-emg/chf-alg3.PNG


gallery_chf_explain:
  - url:  /assets/images/research-emg/chf-exp1.png
    image_path: /assets/images/research-emg/chf-exp1.png

  - url:  /assets/images/research-emg/chf-exp2.png
    image_path: /assets/images/research-emg/chf-exp2.png

gallery_chf_result1:
  - url:  /assets/images/research-emg/chf-tp-noise-sup.png
    image_path: /assets/images/research-emg/chf-tp-snr.png

  - url:  /assets/images/research-emg/chf-exp2.png
    image_path: /assets/images/research-emg/chf-exp2.png


---

## Abstract


<figure style="width: 300px" class="align-left">
  <img src="/assets/images/research-emg/emg-socket-square.png">
  <figcaption>Test caption emg-socket-square</figcaption>
</figure> 

Surface electromyography (sEMG), the least invasive technique among current peripheral neural interface technologies, is one of the most deeply researched and clinically viable methods for extrinsic neural control of prosthetic devices. Thus, vast amount of research works investigating human biomechanics have relied on a sEMG measurement modality. There also exists many past research works investigating feasibility of neural/extrinsic control of bionic devices (such as bionic prosthesis and exoskeleton) using sEMG. While sEMG has been a well established technology and understood quite thoroughly, deploying sEMG technology for closed-loop control of bionic devices is not trivial due to various technical challenges. Since my Master program in MIT Media Lab, I have been investigating the extended sEMG modality in order to use this technology for closed-loop neural control of bionic devices mainly robotic prosthesis. This encompasses design of hardware and firmware/software of an advanced sEMG platform, as well as new electrode interface and signal processing technique.

<!-- {% include gallery2 id="gallery_emgabstract" layout="third" %} Full-stack EMG work with empahsis on real-time control+ human biomechanics. ABST -->

---


## Portable, Real-time, Multi-channel, and Advanced Electromyography Embedded System

### version 1 - 8 channel

{% include gallery2 id="gallery_emg_prototype" caption="EMG System Diagram." %} 

- emg 1 design HW photos + file


{% include gallery2 id="gallery_emg_designconcept" layout="third" caption="Some design thoughts" %}


{% include gallery2 id="gallery_emg_verification" layout="third" caption="Some design thoughts" %}


<figure style="width: 300px" class="align-right">
  <img src="/assets/images/research-emg/EMG_V0_2_SocketComplex3.jpg">
  <figcaption>emg-socket-square</figcaption>
</figure> 

SOCKET COMPLEX EXP

SOCKET COMPLEX EXP

SOCKET COMPLEX EXP

SOCKET COMPLEX EXP

SOCKET COMPLEX EXP

SOCKET COMPLEX EXP

SOCKET COMPLEX EXP


My master thesis and design files are also available as follows:

\[[MIT master thesis link](https://dspace.mit.edu/handle/1721.1/124074)\]
\[[Design files-to be added later through media lab portal]\()]



### version 2 - 16 channel

New EMG - 

More channel for more capa esp using machine learning. 

<figure style="width: 500px" class="align-right">
  <img src="/assets/images/research-emg/system-diagram-exp.PNG">
  <figcaption>emg v2</figcaption>
</figure> 

V2 PROTOTYPE

V2 PROTOTYPE

V2 PROTOTYPE

V2 PROTOTYPE

V2 PROTOTYPE

V2 PROTOTYPE

V2 PROTOTYPE

V2 PROTOTYPE

V2 PROTOTYPE

<figure style="width: 500px" class="align-left">
  <img src="/assets/images/research-emg/system-pfd.PNG">
  <figcaption>P{FDFPFDF</figcaption>
</figure> 

Some design though - power flow diagram

Some design though - power flow diagram

Some design though - power flow diagram

Some design though - power flow diagram

Some design though - power flow diagram

Some design though - power flow diagram

Some design though - power flow diagram

- adaptors
- future arxiv paper.
- codebase for emg1

Related Papers: 


<br/>

---

## Exploratory EMG electrode

Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST


<figure style="width:500px" class="align-left">
  <img src="/assets/images/research-emg/flexible-electrode-abc.PNG">
  <figcaption>Electrode prototype - (c) IEEE</figcaption>
</figure> 

Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST


Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST

Flexible electrode ABST

{% include gallery2 id="gallery_SLIP_demo" layout="third" caption="flexElec demo" %}

DEMONSTRATION WITH PROSTHESIS

DEMONSTRATION WITH PROSTHESIS


- Biorob Paper
- TMRB paper 
- EMBC Ultrasound

- EMG spec during walking



Ultrasound demo
{% include gallery2 id="gallery_US_demo" layout="third" caption="flexElec demo" %}

DEMONSTRATION WITH US


<figure style="width: 500px" class="align-right">
  <img src="/assets/images/research-emg/emg-us-gathered.PNG">
  <figcaption>emg US result</figcaption>
</figure> 

US-SLIP DEMO

US-SLIP DEMO

US-SLIP DEMO

US-SLIP DEMO

US-SLIP DEMO

US-SLIP DEMO

US-SLIP DEMO

US-SLIP DEMO



<br/>

---

## EMG Signal Processing - Impulse Artifact Filtering

EXP CHF CONCEPT

<figure style="width: 500px" class="align-left">
  <img src="/assets/images/research-emg/chf-dsp.PNG">
  <figcaption>CHF</figcaption>
</figure> 

EXP CHF CONCEPT

EXP CHF CONCEPT

EXP CHF CONCEPT

EXP CHF CONCEPT


CHF Alg dev- sSIMPLE

{% include gallery2 id="gallery_chf_alg" layout="third" caption="flexElec demo" %}


CHF Explain

{% include gallery2 id="gallery_chf_explain" layout="third" caption="flexElec demo" %}

GAP

GAP


<figure style="width: 500px" class="align-right">
  <img src="/assets/images/research-emg/chf-exp3.PNG">
  <figcaption>CHF EXP3</figcaption>
</figure> 

CHF-EXP 

CHF-EXP 

CHF-EXP 

CHF-EXP 
CHF-EXP 


CHF RESULT

{% include gallery2 id="gallery_chf_result1" layout="third" caption="flexElec demo" %}



<figure style="width: 500px" class="align-left">
  <img src="/assets/images/research-emg/emg-rms-noise-demo.png">
  <figcaption> CHF RMS DEMO</figcaption>
</figure> 


CHF RESULT


CHF RESULT


CHF RESULT


CHF RESULT


CHF RESULT


CHF RESULT


CHF RESULT


<figure style="width: 500px" class="align-left">
  <img src="/assets/images/research-emg/eemg-walking-demo.png">
  <figcaption> CHF walking</figcaption>
</figure> 

CHF walking demo

CHF walking demo

CHF walking demo

CHF walking demo

CHF walking demo


- impulse artifact filtering
- real-time control of exo + bionic prosthesis
- EMBC paepr 

