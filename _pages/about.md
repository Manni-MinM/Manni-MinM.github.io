---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About me

I'm a Ph.D. student at the University of California, Santa Barbara, working under the supervision of Prof. [Arpit Gupta](https://sites.cs.ucsb.edu/~arpitgupta/) in the Systems and Networking Lab.

My current research lies at the intersection of networking, and machine learning. I aim to build systems that excel in performance, reliability, and capability. I'm currently leading the NetVibe project which is a next-generation network measurement tool.

## Interests

* Network measurement tools and infrastructures
* Machine Learning in Networking
* Resource Optimization in the Cloud

## Selected Publications
For detailed information on publications see: [Publications](https://manni-minm.github.io/publications/)

<ol>
{% assign posts = site.publications | where: "selected", true %}
{% for post in posts reversed %}
  {% include archive-single-paper-custom.html %}
{% endfor %}
</ol>

## Education
 
* Ph.D. in Computer Science -- University of California, Santa Barbara
  *2025 - now, with Prof. Arpit Gupta*
* B.S. in Computer Science -- Amirkabir University of Technology
  *([Fsched](https://github.com/Manni-MinM/fsched): FaaS Platform with Memory Optimization)*

## Thank you for your attention

Have any questions? Feel free to contact me!
