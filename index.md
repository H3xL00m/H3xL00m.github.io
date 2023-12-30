---
layout: default
title: "./h3xl00m/"
description: "Malware Analyst. Red Team Penetration Tester. Photography enthusiast. Researching on the thin line between hardware and software."
---

## About Me

<img class="profile-picture" src="" alt="Profile picture">
<iframe src="https://github.com/sponsors/h3xl00m/button" title="Sponsor h3xl00m" style="border: 0; border-radius: 6px;/*! background-color: beige; */" class="sponsor" width="114" height="32"></iframe>

{% highlight bash %}
$ whoami
h3xl00m: Malware Analyst. Red Team Penetration Tester. Photography enthusiast.
{% endhighlight %}

Dilanka Kaushal Hewage is a dedicated Malware Analyst and Red Team Penetration Tester, currently serving as an Application Security Engineer at Dubai Health Authority. Dilanka, holding a BSc in Computer Science and pursuing an MSc in Cyber Security, is not only immersed in academia but is also a passionate participant in Capture The Flag (CTF) competitions, showcasing his problem-solving prowess in the cybersecurity realm.

In addition to his academic pursuits, Dilanka has earned several prestigious certifications, demonstrating his commitment to excellence in cybersecurity. These certifications, arranged from foundational to advanced levels, include:

    eJPT (eLearnSecurity Junior Penetration Tester)
    CEH Master (Certified Ethical Hacker Master)
    eCPPTv2 (eLearnSecurity Certified Professional Penetration Tester v2)
    CRTP (Certified Red Team Professional)
    CRTE (Certified Red Team Expert)
    CRTO (Certified Red Team Operator)
    OSCP (Offensive Security Certified Professional)
    eCPTXv2 (eLearnSecurity Certified Penetration Tester eXtreme v2)

This impressive array of certifications highlights Dilanka's continuous pursuit of knowledge and expertise, making him a valuable asset in the cybersecurity community. Connect with Dilanka to explore cybersecurity, discuss CTF strategies, and benefit from his extensive knowledge and practical experience. Embark on a cybersecurity journey with Dilanka, where academic excellence, hands-on experience, and a passion for CTFs converge for a comprehensive understanding of the cybersecurity landscape.

## Work

- Application Security Engineer @ [Dubai Health - Dubai]()
- Red Team Penetration Tester @ [AIX Investment Group, Burj Khalifa - Dubai]()
- Red Team Operator @ [DOD - Sri Lanka]

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
