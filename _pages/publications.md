---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Towards a Data-Rate Theorem for State Estimation with Guaranteed Accuracy in Bounded-Noise Environments (with G. Nair), *to appear*, in Proceedings of the *65th IEEE Conference on Decision and Control*, Honolulu, Dec 2026.

<a href="https://www.sciencedirect.com/science/article/pii/S2405896324019499"> Minimum Data-Rate for Emulating a Linear Feedback System</a> (with G. Nair),  *IFAC-PapersOnLine*, vol. 58, no. 17, pp. 350–355, 2024. 

<a href="https://ieeexplore.ieee.org/document/10384053"> Controllability with a finite data-rate of switched linear systems</a> (with D. Liberzon), in Proceedings of the *62nd IEEE Conference on Decision and Control*, Singapore, Dec 2023, pp. 3925-3930. 

<a href="https://epubs.siam.org/doi/10.1137/21M1411871">Estimation Entropy, Lyapunov Exponents, and Quantizer Design for Switched Linear Systems</a> (with D. Liberzon), *SIAM Journal on Control and Optimization*, vol. 61, no. 1, pp. 198-224, 2023. 


<a href ="https://ieeexplore.ieee.org/document/9992626">Controllability of Linear Time-Varying Systems with Quantized Controls and Finite Data-Rate</a> (with D. Liberzon), in Proceedings of the *61st IEEE Conference on Decision and Control*, Cancún, Mexico, Dec 2022, pp. 3669-3674.
    
<a href ="https://dl.acm.org/doi/10.1145/3447928.3456645">Quantizer Design for Linear Switched Systems with Minimal Data-Rate</a> (with D. Liberzon), in Proceedings of the *24th ACM International Conference on Hybrid Systems: Computation and Control* (HSCC 2021), Nashville, TN (online), May 2021.

        
<a href="https://ieeexplore.ieee.org/document/9030155">Estimation Entropy for Regular Linear Switched Systems</a> (with D.Liberzon), in Proceedings of the *58th IEEE Conference on Decision and Control*, Nice, France, Dec 2019, pp. 5754-5759.
        
<a href ="https://www.sciencedirect.com/science/article/pii/S2405896319320117">How to park a car blindfolded</a> (with D. Liberzon), in Proceedings of the *8th IFAC Workshop on Distributed Estimation and Control in Networked Systems* (NecSys), Chicago, IL, Sep 2019, pp. 211-216.

Control of Pneumatic Valves with Friction Using Algebraic Estimators (with C. Garcia and P. S. P. da Silva) *ABCM International Congress of Mechanical Engineering* (COBEM), Dec 2017

<a href ="https://ieeexplore.ieee.org/document/7569739">Position Estimation from Range Measurements Using Adaptive Networks</a> (with Y. P. Bergamo and C. G. Lopes), in Proceedings of the *9th IEEE Sensor Array and Multichannel Signal Processing Workshop* (SAM), Rio de Janeiro, Brazil, Jul 2016, pp. 1-5


{% comment %}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
