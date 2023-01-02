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
__K. Ram Prabhakar__\*, Susmit Agarwal\*, and R. Venkatesh Babu  
_IEEE Transactions on Computational Imaging 2021_
* **PA-Fuse: A Deep Supervised Approach for Fusion of Photoacoustic Images with Distinct Reconstruction Characteristics**  
N. Awasthi, __K. Ram Prabhakar__, S. K. Kalva, M. Pramanik, R. Venkatesh Babu, and Phaneendra K. Yalavarthy  
_JOSA Biomedical Optics Express 2019_

## Conferences
* Paper title  
K. Ram Prabhakar, et al.  
_ECCV 2020_
* Paper title
