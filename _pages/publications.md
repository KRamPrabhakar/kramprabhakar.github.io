---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on <u><a href="https://scholar.google.com/citations?user=gBhmvr8AAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journals
* **Self-Gated Memory Recurrent Network for Efficient Scalable HDR Deghosting**  
K. Ram Prabhakar\*, Susmit Agarwal\*, and R. Venkatesh Babu  
_IEEE Transactions on Computational Imaging 2021_  
\[ [paper](https://ieeexplore.ieee.org/document/9540317?source=authoralert), [code](https://github.com/Susmit-A/HDRRNN) \]
* **PA-Fuse: A Deep Supervised Approach for Fusion of Photoacoustic Images with Distinct Reconstruction Characteristics**  
N. Awasthi, K. Ram Prabhakar, S. K. Kalva, M. Pramanik, R. Venkatesh Babu, and Phaneendra K. Yalavarthy  
_JOSA Biomedical Optics Express 2019_

## Conferences
* **A Few-shot approach to MRI-based Knee Disorder Diagnosis using Fuzzy Layers**  
Mohana Singh, K Ram Prabhakar, P Vishwanath, Murali Poduval, Arpan Pal, Jayavardhana Gubbi  
_ICVGIP 2022_ \[**Oral**\]
* **Few-Shot Cross-Sensor Domain Adaptation between SAR and Multispectral Data**  
K. Ram Prabhakar, V H Krishna, J Gubbi, A Pal, P Balamuralidhar  
_IEEE IGARSS 2022_
* **Improving SAR and Optical Image Fusion for LULC Classification with Domain Knowledge**  
K. Ram Prabhakar\*, V H Krishna\*, J Gubbi, A Pal, P Balamuralidhar  
_IEEE IGARSS 2022_
* **Few-Shot Domain Adaptation for Low Light RAW Image Enhancement**  
K Ram Prabhakar, Vishal Vinod*, Nihar Ranjan Sahoo*, and R Venkatesh Babu  
_BMVC 2021_ \[**Best Student Paper (Runner up) award**\]
