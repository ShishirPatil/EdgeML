---
layout: page
title: ProtoNN
category: Algorithms
---

ProtoNN is a novel, k-nearest neighbors (kNN) based general supervised learning algorithm that can be deployed on the tiniest of iot devices. ProtoNN produces state-of-the-art accuracies for typical iot prediction tasks, with just about 16kB of memory size. kNN is a popular choice for machine learning solution for general classification problems owing to its simplicity, generality, and interpretability. ProtoNN, in addition, enjoys key properties to be able to support real-time iot applications 
  - Extremely small sizes (a few kB), and 
  - Extremely small prediction times. 
  
ProtoNN learns prototypes to represent the entire training dataset as well as labels for each prototype -- this boosts prediction accuracies in many applications and provides additional flexibility, and seamless generalization to multi-label or ranking problems. 

As in the case of [Bonsai]({{ site.baseurl}}/Algorithms/Bonsai/), ProtoNN has been deployed successfully on microcontrollers tinier than a grain of rice such as the ARM Cortex M0 with just 2 KB RAM; it can accurately and efficiently predict on the tiniest of IoT boards such as the Arduino Pro Mini based on an 8 bit Atmel ATmega328P microcontroller operating at 8 MHz without any floating point support in hardware, with 2 KB RAM and 32 KB read-only flash memory.

Please refer to our [ICML paper]({{ site.baseurl}}{{ site.customurl.protonn.pdf }}) for more details about the model and training algorithm.  

**Downloads:**<br>
<span class="publ-linklist">
    [<a href="{{ site.baseurl}}{{ site.customurl.protonn.pdf }}">PDF</a>]
    [\[Code Coming Soon\]]()
</span>
