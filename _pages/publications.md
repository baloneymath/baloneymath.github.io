---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}
You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{: .notice--info}

<!---
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

<br>

Journal Articles
======
* 2020
  ### J3. Challenges and Opportunities Toward Fully Automated Analog Layout Design
     * Invited
     * **Hao Chen***, Mingjie Liu*, Xiyuan Tang*, Keren Zhu*, Nan Sun, and David Z. Pan (* equal contribution)
     * Journal of Semiconductors (JoS), 2020.
     
  ### J2. [MAGICAL: An Open-Source Fully Automated Analog IC Layout System from Netlist to GDSII](https://doi.org/10.1109/MDAT.2020.3024153)
     * Invited
     * **Hao Chen***, Mingjie Liu*, Biying Xu*, Keren Zhu*, Xiyuan Tang, Shaolan Li, Yibo Lin, Nan Sun, and David Z. Pan (* equal contribution)
     * IEEE Design and Test (D&T), 2020.
     
  ### J1. [A DAG-Based Algorithm for Obstacle-Aware Topology-Matching On-Track Bus Routing](https://ieeexplore.ieee.org/abstract/document/9119108)
     * Chen-Hao Hsu, Shao-Chun Hung, **Hao Chen**, Fan-Keng Sun, and Yao-Wen Chang
     * IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2020.

Conference Papers
======

* 2020
  ### C6. Exploring Logic Optimizations with Reinforcement Learning and Graph Convolutional Network
     * Keren Zhu, Mingjie Liu, **Hao Chen**, Zheng Zhao, and David Z. Pan
     * ACM/IEEE International Conference on Computer-Aided Design (ICCAD), Virtual Event, Nov. 16-20, 2020. (accepted)

  ### C5. [Toward Silicon-Proven Detailed Routing for Analog and Mixed-Signal Circuits](https://doi.org/10.1145/3400302.3415660)
     * [Preprint](/files/ICCAD20_ar.pdf){: .btn}
     * **Hao Chen**, Keren Zhu, Mingjie Liu, Xiyuan Tang, Nan Sun, and David Z. Pan
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), Virtual Event, Nov. 2-5, 2020.
  
  ### C4. [Effective Analog/Mixed-Signal Circuit Placement Considering System Signal Flow](https://doi.org/10.1145/3400302.3415625)
     * [Preprint](/files/ICCAD20_ap.pdf){: .btn}
     * Keren Zhu, **Hao Chen**, Mingjie Liu, Xiyuan Tang, Nan Sun, and David Z. Pan
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), Virtual Event, Nov. 2-5, 2020.
     
* 2019

  ### C3. [Disjoint-Support Decomposition and Extraction for Interconnect-Driven Threshold Logic Synthesis](https://doi.org/10.1145/3316781.3317801)
     * [Preprint](/files/dac19_thre.pdf){: .btn}
     * **Hao Chen**, Shao-Chun Hung, and Jie-Hong R. Jiang
     * ACM/IEEE Design Automation Conference (DAC), Las Vegas, NV, Jun. 2-6, 2019.
  
  ### C2. [A DAG-Based Algorithm for Obstacle-Aware Topology-Matching On-Track Bus Routing](https://doi.org/10.1145/3316781.3317740)
     * [Preprint](/files/dac19_bus.pdf){: .btn}
     * Chen-Hao Hsu, Shao-Chun Hung, **Hao Chen**, Fan-Keng Sun, and Yao-Wen Chang
     * ACM/IEEE Design Automation Conference (DAC), Las Vegas, NV, Jun. 2-6, 2019.

* 2018
  
  ### C1. [A Multithreaded Initial Detailed Routing Algorithm Considering Global Routing Guides](https://doi.org/10.1145/3240765.3240777)
     * [Preprint](/files/iccad18_dr.pdf){: .btn}
     * Fan-Keng Sun, **Hao Chen**, Ching-Yu Chen, Chen-Hao Hsu, and Yao-Wen Chang
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), San Diego, CA, Nov. 5-8, 2018.
