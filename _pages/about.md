---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div id="about"></div>

## About

Hi, I'm a second-year PhD student at [University of Southern California](https://www.usc.edu), advised by [Professor Corey E. Baker](https://viterbi.usc.edu/directory/faculty/Baker/Corey).

I am passionate about exploring a wide range of applications in machine learning, particularly those that address real-world problems. I enjoy discussing ideas, asking questions, and thinking deeply about complex systems. Please contact me directly if interested!

I am actively seeking internship positions in recommendation systems and autonomous systems.

[Email](mailto:yulinxu@usc.edu) / [Wechat](../images/wechat.jpg)


### News

- **[May 2026]** One paper accepted by ICML 2026
- **[Apr 2026]** One paper accepted by ICMR 2026
- **[Apr 2026]** One paper accepted by SIGIR 2026
- **[Aug 2025]** Started my PhD
- **[Jul 2025]** Invited to serve as KDD 2026 Datasets and Benchmarks Track reviewer
- **[May 2025]** One paper accepted by KDD 2025 ADS Track
- **[Mar 2025]** To be an incoming PhD student at USC!!


<div id="research"></div>

## Research

My research interests include machine learning methods and their applications in recommendation systems and autonomous systems.

<!-- More research content can be added here later. -->


<div id="publications"></div>

## Publications

{% assign pubs = site.publications | sort: "date" | reverse %}

{% for pub in pubs %}

### {{ pub.title }}

{{ pub.excerpt | markdownify }}

{% if pub.venue %}
*{{ pub.venue }}*, {{ pub.date | date: "%Y" }}
{% endif %}

{% if pub.paperurl and pub.paperurl != "" %}
[Paper]({{ pub.paperurl }})
{% endif %}

{% endfor %}


<div id="misc"></div>

## Life

<!-- Life content can be added here later. -->
