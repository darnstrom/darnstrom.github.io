---
layout: about
title: About
permalink: /
description: Senior Researcher </br> Ericsson Reserach • Decision and Control

profile:
  align: right 
  image: arnstrom_round.png
  address: > #<p> <i class="fa fa-envelope"></i> daniel.arnstrom@it.uu.se </p> <p> <i class="fa fa-github"></i> darnstrom </p>

news: false # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---
<hr style="border:solid 2px">

# About me

I am a **Senior Researcher** at **Ericsson Research** in the Decision and Control group. My work focuses on the intersection of reliability and performance, specifically regarding **embedded optimization** and **real-time Model Predictive Control (MPC)**. I investigate the reliability of optimization-based controllers across computational, safety, security, and communication dimensions.

---

### Experience & Education

Before joining Ericsson, I developed my research at several leading institutions:

* **Postdoctoral Researcher (2023–2025)**  
  [Division of Systems and Control](http://www.it.uu.se/about_us/divisions/systems_and_control), Uppsala University. Worked with [André Teixeira](https://www.andre-teixeira.eu/).
* **Visiting Researcher**  
  ETH Zurich. Spent six months in [Melanie Zeilinger's group](https://idsc.ethz.ch/the-institute/people/person-detail.zeilinger.html) through an [NCCR Automation](https://nccr-automation.ch/) fellowship.
* **PhD in Electrical Engineering (2023)**  
  Linköping University. Specialized in Automatic Control with my thesis: [*"Real-Time Certified MPC: Reliable Active-Set QP Solvers"*](https://doi.org/10.3384/9789180752190). Supervisor: [Daniel Axehill](https://liu.se/en/employee/danax42)
* **M.Sc. & Licentiate Degrees**  
  Linköping University (2018, 2021).

---

### Research Focus: Efficient and Reliable Real-Time Optimization

The core of my research is ensuring that optimization solvers used in real-time systems are guaranteed to find solutions within strict time frames. Research interests include: 

1.  **Development of Efficient Solvers:** Creating optimization solvers tailored for specific hardware and problem structures.
    * *Example:* [**DAQP**](https://github.com/darnstrom/daqp) – A dual active-set QP solver.
2.  **Complexity Certification:** Developing methods to determine worst-case computational complexity bounds for solvers.
    * *Example:* [**ASCertain.jl**](https://github.com/darnstrom/ASCertain.jl) – A Julia package for certifying the complexity of active-set solvers.
3.  **Advanced Optimization Specifications** Amending existing optimization methods for constraints and objectives arising in advanced applications (for example, logic constraints, prioritized constraints, and game-theoretic objectives.)


<hr style="border:solid 2px">
