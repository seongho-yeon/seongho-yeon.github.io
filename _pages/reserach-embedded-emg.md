---
layout: single
title: Advanced Electromyography for Human Biomechanics and Bionics Research
permalink: /docs/research/research-embedded-emg
author_profile: false
classes: wide

gallery_emgabstract:
  - url:  /assets/images/research-emg/emg-socket-square.png
    image_path: /assets/images/research-emg/emg-socket-square.png

gallery_emg1:
  - url:  /assets/images/research-emg/system-diagram.PNG
    image_path: /assets/images/research-emg/system-diagram.PNG

  - url:  /assets/images/research-emg/hw_summary.jpg
    image_path: /assets/images/research-emg/hw_summary.jpg
    # title: "EMG Board Summary"

gallery_emg2:
  - url:  /assets/images/research-emg/afe-architecture.PNG
    image_path: /assets/images/research-emg/afe-architecture.PNG

  - url:  /assets/images/research-emg/os-schedule-scheme.PNG
    image_path: /assets/images/research-emg/os-schedule-scheme.PNG

  - url:  /assets/images/research-emg/memory-buffering.PNG
    image_path: /assets/images/research-emg/memory-buffering.PNG

  # - url:  /assets/images/research-emg/system-pfd.PNG
  #   image_path: /assets/images/research-emg/system-pfd.PNG

---

## Abstract


<figure style="width: 300px" class="align-left">
  <img src="/assets/images/research-emg/emg-socket-square.png">
  <figcaption>Test caption emg-socket-square</figcaption>
</figure> 

Surface electromyography (sEMG), the least invasive technique among current peripheral neural interface technologies, is one of the most deeply researched and clinically viable methods for extrinsic neural control of prosthetic devices. Thus, vast amount of research works investigating human biomechanics have relied on a sEMG measurement modality. There also exists many past research works investigating feasibility of neural/extrinsic control of bionic devices (such as bionic prosthesis and exoskeleton) using sEMG. While sEMG has been a well established technology and understood quite thoroughly, deploying sEMG technology for closed-loop control of bionic devices is not trivial due to various technical challenges. Since my Master program in MIT Media Lab, I have been investigating the extended sEMG modality in order to use this technology for closed-loop neural control of bionic devices mainly robotic prosthesis. This encompasses design of hardware and firmware/software advanced measurement platform, better electrode interface, and even signal processing technique.

<!-- {% include gallery2 id="gallery_emgabstract" layout="third" %} Full-stack EMG work with empahsis on real-time control+ human biomechanics. ABST -->

---


## Portable, Real-time, Multi-channel, and Advanced Electromyography Embedded System


{% include gallery2 id="gallery_emg1" caption="EMG System Diagram." %} 

- emg 1 design HW photos + file


{% include gallery2 id="gallery_emg2" layout="third" caption="Some design thoughts" %}


\[[master thesis link](https://dspace.mit.edu/handle/1721.1/124074)\]


- emg2 design photos + file
- firmware?
- adaptors

- future arxiv paper.
- codebase for emg1

Related Papers: 
---

## Exploratory EMG electrode

- fPCB electrode Photo
- Biorob Paper
- TMRB paper 
- EMBC Ultrasound

- EMG spec during walking

---

## EMG signal processing 

- impulse artifact filtering
- real-time control of exo + bionic prosthesis
- EMBC paepr 

