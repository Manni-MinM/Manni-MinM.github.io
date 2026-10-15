---
permalink: /
layout: home
title: "Manni Moghimi"
excerpt: "About me"
author_profile: false
subtitle: "Ph.D. Student in Computer Science, [University of California, Santa Barbara](https://www.cs.ucsb.edu/)"
profile_image: "profile.jpg"
profile_caption: "manni [at] ucsb [dot] edu"
email_user: "manni"
email_domain: "ucsb.edu"
contact_note: "The best way to reach me is by email!"
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

**I believe networking research runs on data, and I build the infrastructure that enables it.** I lead [NetVibe](/projects/netvibe/){:target="_blank" rel="noopener"}, a continuous broadband measurement platform, and [Pramana](/projects/pramana/), a platform for building real-world network datasets by running actual applications, not simulations, under controlled and diverse network conditions.

**Biography:** I'm a Ph.D. student in the Systems and Networking Lab at UC Santa Barbara, advised by Prof. [Arpit Gupta](https://sites.cs.ucsb.edu/~arpitgupta/){:target="_blank" rel="noopener"}. Before that, I received my B.S. in Computer Engineering from Amirkabir University of Technology.

**Interests:**

* Network measurement
* Agentic pipelines for networking and self-driving networks
* Data-driven broadband policy
* Broadband and last-mile network performance
* LEO satellite networks

## News

<table class="alf-news">
{% for item in site.data.news limit: 5 %}
  <tr>
    <th scope="row">{{ item.date }}</th>
    <td>{{ item.text | markdownify | remove: "<p>" | remove: "</p>" }}</td>
  </tr>
{% endfor %}
</table>

## Selected publications

<ol class="alf-pubs">
{% assign posts = site.publications | where: "selected", true %}
{% for post in posts reversed %}
  {% include archive-single-paper-custom.html %}
{% endfor %}
</ol>

## Education

<ul class="alf-edu">
  <li>
    <span><strong>Ph.D. in Computer Science</strong>, University of California, Santa Barbara<br><em>Advised by Prof. Arpit Gupta</em></span>
    <span class="alf-edu-date">2025 – 2030 (expected)</span>
  </li>
  <li>
    <span><strong>B.S. in Computer Engineering</strong>, Amirkabir University of Technology</span>
    <span class="alf-edu-date">2020 – 2025</span>
  </li>
</ul>
