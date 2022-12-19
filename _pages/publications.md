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

Book Chapters
======
* 2022
  ### B2. [Machine Learning Applications in Electronic Design Automation](https://www.barnesandnoble.com/w/machine-learning-applications-in-electronic-design-automation-haoxing-ren/1141727406)
     * Steven M. Burns, **Hao Chen**, Tonmoy Dhar, Ramesh Harjani, Jiang Hu, Nibedita Karmokar, Kishor Kunal, Yaguang Li, Yishuang Lin, Mingjie Liu, Meghna Madhusudan, Parijat Mukherjee, David Z. Pan, Jitesh Poojary, S. Ramprasath, Sachin S. Sapatnekar, Arvind K. Sharma, Wenbin Xu, Soner Yaldiz, and Keren Zhu (equal contribution)
     * Springer, 2022. 
  
  ### B1. [CAD for Analog/Mixed-Signal Integrated Circuits](https://www.amazon.com/Advances-Semiconductor-Technologies-Selected-Conventional/dp/1119869587)
     * Mohamed B. Alawieh, Ahmet F. Budak, Hao Chen, Mingjie Liu, David Z. Pan, Wei Shi, Xiyuan Tang, Shuhan Zhang, and Keren Zhu (equal contribution)
     * _Advances in Semiconductor Technologies: Selected Topics Beyond Conventional CMOS_, Wiley-IEEE Press., 2022

Journal Articles
======
* 2022
  ### J4. [Tutorial and Perspectives on MAGICAL: A Silicon-Proven Open-Source Analog IC Layout System](https://ieeexplore.ieee.org/document/9769692)
     * Invited
     * Keren Zhu, **Hao Chen**, Mingjie Liu, and David Z. Pan (\* equal contribution)
     * IEEE Transactions on Circuits and Systems II (TCAS-II), 2022.
     
* 2020
  ### J3. [Challenges and Opportunities Toward Fully Automated Analog Layout Design](http://doi.org/10.1088/1674-4926/41/11/111407)
     * Invited
     * **Hao Chen**\*, Mingjie Liu\*, Xiyuan Tang\*, Keren Zhu\*, Nan Sun, and David Z. Pan (\* equal contribution)
     * Journal of Semiconductors (JoS), 2020.
     
  ### J2. [MAGICAL: An Open-Source Fully Automated Analog IC Layout System from Netlist to GDSII](https://doi.org/10.1109/MDAT.2020.3024153)
     * Invited
     * **Hao Chen**\*, Mingjie Liu\*, Biying Xu\*, Keren Zhu\*, Xiyuan Tang, Shaolan Li, Yibo Lin, Nan Sun, and David Z. Pan (\* equal contribution)
     * IEEE Design and Test (D&T), 2020.
     
  ### J1. [A DAG-Based Algorithm for Obstacle-Aware Topology-Matching On-Track Bus Routing](https://ieeexplore.ieee.org/abstract/document/9119108)
     * Chen-Hao Hsu, Shao-Chun Hung, **Hao Chen**, Fan-Keng Sun, and Yao-Wen Chang
     * IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2020.

Conference Papers
======
* 2023
  ### C15. [Reinforcement Learning Guided Custom Detailed Routing]()
     * **Hao Chen**, Kai-Chieh Hsu, Walker J. Turner, Po-Hsuan Wei, Keren Zhu, David Z. Pan, and Haoxing Ren
     * ACM International Symposium on Physical Design (ISPD), Virtual Event, Mar. 26-29, 2023.

* 2022
  ### C14. [TAG: Learning Circuit Spatial Embedding From Layouts]()
     * Keren Zhu, **Hao Chen**, Walker J. Turner, George F. Kokai, Po-Hsuan Wei, David Z. Pan, and Haoxing Ren
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), San Diego, CA, Oct. 30 - Nov. 3, 2022.

  ### C13. [AutoCRAFT: Layout Automation for Custom Circuits in Advanced FinFET Technologies](https://doi.org/10.1145/3505170.3511044)
     * **Hao Chen**, Walker J. Turner, Sanquan Song, Keren Zhu, George F. Kokai, Brian Zimmer, C. Thomas Gray, Brucek Khailany, David Z. Pan, and Haoxing Ren
     * ACM International Symposium on Physical Design (ISPD), Virtual Event, Canada, Mar. 27-30, 2022.
 
  ### C12. [Routability-Aware Placement for Advanced FinFET Mixed-Signal Circuits using Satisfiability Modulo Theories]()
     * **Hao Chen**, Walker J. Turner, David Z. Pan, and Haoxing Ren
     * IEEE/ACM Design, Automation and Test in Europe (DATE), Antwerp, Belgium, Mar. 14-23, 2022.

  ### C11. [Automating Analog Constraint Extraction: From Heuristics to Learning](https://ieeexplore.ieee.org/abstract/document/9712488)
     * Invited
     * Keren Zhu, **Hao Chen**, Mingjie Liu, and David Z. Pan
     * IEEE/ACM Asia and South Pacific Design Automation Conference (ASP-DAC), Virtual Event, Taiwan, Jan. 17-20, 2022.
     
  ### C10. [Generative-Adversarial-Network-Guided Well-Aware Placement for Analog Circuits](https://ieeexplore.ieee.org/abstract/document/9712592)
     * Keren Zhu, **Hao Chen**, Mingjie Liu, Xiyuan Tang, Wei Shi, Nan Sun, and David Z. Pan
     * IEEE/ACM Asia and South Pacific Design Automation Conference (ASP-DAC), Virtual Event, Taiwan, Jan. 17-20, 2022.

* 2021
  ### C9. [OpenSAR: An Open Source Automated End-to-end SAR ADC Compiler](https://ieeexplore.ieee.org/abstract/document/9643494)
     * Mingjie Liu, Xiyuan Tang, Keren Zhu, **Hao Chen**, Nan Sun, and David Z. Pan
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), Virtual Event, USA, Nov. 01-04, 2021.
     
  ### C8. [Universal Symmetry Constraint Extraction for Analog and Mixed-Signal Circuits with Graph Neural Networks](https://doi.org/10.1109/DAC18074.2021.9586211)
     * [Preprint](/files/DAC21_ac.pdf){: .btn}
     * **Hao Chen**, Keren Zhu, Mingjie Liu, Xiyuan Tang, Nan Sun, and David Z. Pan
     * ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, Jul. 11-15, 2021.
     
  ### C7. [MAGICAL 1.0: An Open-Source Fully-Automated AMS Layout Synthesis Framework Verified With a 40-nm 1GS/s ∆Σ ADC](https://ieeexplore.ieee.org/document/9431521)
     * [Preprint](/files/CICC21_magical.pdf){: .btn}
     * **Hao Chen**\*, Mingjie Liu\*, Xiyuan Tang\*, Keren Zhu\*, Abhishek Mukherjee, Nan Sun, and David Z. Pan (\* equal contribution)
     * IEEE Custom Integrated Circuits Conference (CICC), Virtual Event, USA, Apr. 25-28, 2021.
     
* 2020     
  ### C6. [Exploring Logic Optimizations with Reinforcement Learning and Graph Convolutional Network](https://doi.org/10.1145/3380446.3430622)
     * [Preprint](/files/MLCAD20_ls.pdf){: .btn}
     * Keren Zhu, Mingjie Liu, **Hao Chen**, Zheng Zhao, and David Z. Pan
     * ACM/IEEE Workshop on Machine Learning for CAD (MLCAD), Virtual Event, Iceland, Nov. 16-20, 2020.

  ### C5. [Toward Silicon-Proven Detailed Routing for Analog and Mixed-Signal Circuits](https://doi.org/10.1145/3400302.3415660)
     * [Preprint](/files/ICCAD20_ar.pdf){: .btn}
     * **Hao Chen**, Keren Zhu, Mingjie Liu, Xiyuan Tang, Nan Sun, and David Z. Pan
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), Virtual Event, USA, Nov. 2-5, 2020.
  
  ### C4. [Effective Analog/Mixed-Signal Circuit Placement Considering System Signal Flow](https://doi.org/10.1145/3400302.3415625)
     * [Preprint](/files/ICCAD20_ap.pdf){: .btn}
     * Keren Zhu, **Hao Chen**, Mingjie Liu, Xiyuan Tang, Nan Sun, and David Z. Pan
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), Virtual Event, USA, Nov. 2-5, 2020.
     
* 2019

  ### C3. [Disjoint-Support Decomposition and Extraction for Interconnect-Driven Threshold Logic Synthesis](https://doi.org/10.1145/3316781.3317801)
     * [Preprint](/files/DAC19_thre.pdf){: .btn}
     * **Hao Chen**, Shao-Chun Hung, and Jie-Hong R. Jiang
     * ACM/IEEE Design Automation Conference (DAC), Las Vegas, NV, Jun. 2-6, 2019.
  
  ### C2. [A DAG-Based Algorithm for Obstacle-Aware Topology-Matching On-Track Bus Routing](https://doi.org/10.1145/3316781.3317740)
     * [Preprint](/files/DAC19_bus.pdf){: .btn}
     * Chen-Hao Hsu, Shao-Chun Hung, **Hao Chen**, Fan-Keng Sun, and Yao-Wen Chang
     * ACM/IEEE Design Automation Conference (DAC), Las Vegas, NV, Jun. 2-6, 2019.

* 2018
  
  ### C1. [A Multithreaded Initial Detailed Routing Algorithm Considering Global Routing Guides](https://doi.org/10.1145/3240765.3240777)
     * [Preprint](/files/ICCAD18_dr.pdf){: .btn}
     * Fan-Keng Sun, **Hao Chen**, Ching-Yu Chen, Chen-Hao Hsu, and Yao-Wen Chang
     * IEEE/ACM International Conference on Computer-Aided Design (ICCAD), San Diego, CA, Nov. 5-8, 2018.
