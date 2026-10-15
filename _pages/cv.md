---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

<div class="alf-content alf-cv" markdown="1">

## Education

<ul class="alf-edu">
  <li>
    <span><strong>Ph.D. in Computer Science</strong>, University of California, Santa Barbara<br><em>Advised by Prof. Arpit Gupta · GPA: 4.0/4.0</em></span>
    <span class="alf-edu-date">2025 – 2030 (expected)</span>
  </li>
  <li>
    <span><strong>B.S. in Computer Engineering</strong>, Amirkabir University of Technology</span>
    <span class="alf-edu-date">2020 – 2025</span>
  </li>
</ul>

## Research

<ul class="alf-edu">
  <li>
    <span><strong>NetVibe</strong>, Project lead · UC Santa Barbara<br>A continuous network quality measurement platform that uses lightweight probes to bridge the gap between measured and experienced network quality. The project spans multiple research tracks and a real product, and I manage a team of up to five students to carry both forward.</span>
    <span class="alf-edu-date">2025 – present</span>
  </li>
  <li>
    <span><strong>Pramana</strong>, Project lead · UC Santa Barbara<br>A platform for building real-world network datasets by running actual applications under controlled and diverse network conditions (ACM HotNets 2026).</span>
    <span class="alf-edu-date">2026 – present</span>
  </li>
  <li>
    <span><strong>KubeDSM</strong>, Undergraduate researcher · Amirkabir University of Technology<br>Kubernetes scheduling and live migration for cloud-assisted edge clusters (<em>Cluster Computing</em>, 2026). I designed the experiments and ran the evaluation. Advised by Prof. Mahmoud Momtazpour.</span>
    <span class="alf-edu-date">2025</span>
  </li>
</ul>

## Publications

<ol class="alf-pubs">
{% for post in site.publications reversed %}
  {% include archive-single-paper-custom.html %}
{% endfor %}
</ol>

## Teaching

<ul class="alf-edu">
  <li>
    <span><strong>Teaching Assistant</strong>, CS 171: Distributed Systems · UC Santa Barbara<br><em>Instructor: Prof. Amr El Abbadi</em></span>
    <span class="alf-edu-date">Fall 2025</span>
  </li>
</ul>

## Skills

<ul class="alf-skills">
  <li><strong>Languages:</strong> Go, Python, TypeScript, Rust</li>
  <li><strong>Infrastructure:</strong> Docker, Kubernetes, Google Cloud, Pulumi, GitHub Actions CI/CD, Linux</li>
  <li><strong>Data:</strong> PostgreSQL, ClickHouse, InfluxDB, SQLite</li>
  <li><strong>AI and automation:</strong> LangChain, LangGraph, LLM agents, Model Context Protocol (MCP)</li>
</ul>

</div>
