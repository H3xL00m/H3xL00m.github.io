---
layout: default
title: "./h3xl00m/"
description: "Engineer. Developer. Photography enthusiast. Researching on the thin line between hardware and software."
---

## About Me

<img class="profile-picture" src="images/profile.png" alt="Profile picture">
<iframe src="https://github.com/sponsors/h3xl00m/button" title="Sponsor h3xl00m" style="border: 0; border-radius: 6px;/*! background-color: beige; */" class="sponsor" width="114" height="32"></iframe>

{% highlight bash %}
$ whoami
h3xl00m: phd. engineer. developer. photography enthusiast.
{% endhighlight %}

João Pedro Dias is part researcher on the thin line between hardware and software, and part Software Engineer. He has a BSc+MSc in [Informatics and Computing Engineering](https://sigarra.up.pt/feup/en/cur_geral.cur_view?pv_ano_lectivo=2018&pv_origem=CUR&pv_tipo_cur_sigla=MI&pv_curso_id=742) by the [Faculty of Engineering, University of Porto (FEUP)](https://sigarra.up.pt/feup/en/WEB_PAGE.INICIAL). He earned his Ph.D. in Informatics Engineering fromFEUP in 2022, while receiving a grant from the FCT. He maintains a Software Engineer position as a day-to-day job at Kuehne+Nagel. Since 2017, he has been an Invited Assistant Professor at FEUP, where he teaches courses in Software Engineering, Operating Systems, among others. He has (co-)supervised  +5 MSc dissertations and contributed to two projects at LIACC and INESC TEC. His research focuses on Internet-of-Things systems, software engineering, security and privacy, and his work has been published in several top-tier conferences and journals ([h-index 16, i10-index 22](https://scholar.google.com/citations?user=sQ2vKI0AAAAJ)). In his free time, he enjoys participating in Capture The Flag competitions, experimenting with Software-defined Radio, building web applications, reverse-engineering hardware, and photographing while wandering in nature.

## Work

- Software Engineer @ [Kuehne+Nagel](https://kuehne-nagel.com)
- Invited Assistant Professor @ [FEUP](https://sigarra.up.pt/feup/en/WEB_PAGE.INICIAL)

## Research Interests

- Software Engineering
  - Design Patterns, Development Methodologies, Software Development, Edge/Fog/Cloud Computing, Live Programming, Visual Programming and Fault-Tolerance
- Internet-of-Things
  - Systems of Systems, Reference Architectures, Development Toolkits and IDEs
- Security & Privacy
  - Surveillance Self-Defense, Capture the Flag (CTF) and Security Education

## Recent Publications

{% assign counter = 0 %}

{% for pub in site.data.publications.confs limit:3 %}

{% assign counter = counter | plus:1 %}

<div class="pub-item">
<div class="pub-title"><span>[{{ counter }}]</span><a href="{{ pub.url }}" target="_blank"><b>{{ pub.title }}</b></a><br></div>
<div><i class="ri-group-line"></i> {{ pub.authors }}</div>
<div><i class="ri-book-3-line"></i>  {{ pub.conference }}</div>
</div>

{% endfor %}

{% for pub in site.data.publications.journals limit:2 %}

{% assign counter = counter | plus:1 %}

<div class="pub-item">
<div class="pub-title"><span>[{{ counter }}]</span><a href="{{ pub.url }}" target="_blank"><b>{{ pub.title }}</b></a><br></div>
<div><i class="ri-group-line"></i> {{ pub.authors }}</div>
<div><i class="ri-book-3-line"></i>  {{ pub.conference }}</div>
</div>

{% endfor %}

<a href="/publications"><i class="ri-add-circle-line"></i> **View More**</a>