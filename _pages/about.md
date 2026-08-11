---
permalink: /
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section id="about" class="home-hero">

<div class="home-hero__text">

<h1>Yulin Xu</h1>

<p class="home-subtitle">
Ph.D. Student · University of Southern California
</p>

<p>
Hi, I'm a second-year PhD student at
<a href="https://www.usc.edu">University of Southern California</a>,
advised by
<a href="https://viterbi.usc.edu/directory/faculty/Baker/Corey">Professor Corey E. Baker</a>.
</p>

<p>
I am passionate about exploring a wide range of applications in machine learning, particularly those that address real-world problems. I enjoy discussing ideas, asking questions, and thinking deeply about complex systems.
</p>

<p>
I am actively seeking internship positions in recommendation systems and autonomous systems.
</p>

<p class="home-links">
<a href="mailto:yulinxu@usc.edu">Email</a>
<span>·</span>
<a href="{{ site.author.googlescholar }}">Google Scholar</a>
<span>·</span>
<a href="{{ site.author.github }}">GitHub</a>
<span>·</span>
<a href="{{ site.url }}{{ site.baseurl }}/images/wechat.jpg">Wechat</a>
</p>

</div>

<div class="home-hero__photo">
<img src="{{ site.url }}{{ site.baseurl }}/images/profile.png" alt="Yulin Xu">
</div>

</section>


<h2>News</h2>

<ul class="news-list">
  <li><strong>May 2026</strong> One paper accepted by ICML 2026</li>
  <li><strong>Apr 2026</strong> One paper accepted by ICMR 2026</li>
  <li><strong>Apr 2026</strong> One paper accepted by SIGIR 2026</li>
  <li><strong>Aug 2025</strong> Started my PhD</li>
  <li><strong>Jul 2025</strong> Invited to serve as KDD 2026 Datasets and Benchmarks Track reviewer</li>
  <li><strong>May 2025</strong> One paper accepted by KDD 2025 ADS Track</li>
  <li><strong>Mar 2025</strong> To be an incoming PhD student at USC!!</li>
</ul>


<section id="research" class="home-section">

<h2>Research</h2>

<p>
My research interests include machine learning methods and their applications in recommendation systems and autonomous systems.
</p>

</section>


<section id="publications" class="home-section">

<h2>Publications</h2>

{% assign pubs = site.publications | sort: "date" | reverse %}

{% for pub in pubs %}

<div class="pub-item">

<div class="pub-venue">
{{ pub.venue }} · {{ pub.date | date: "%Y" }}
</div>

<h3 class="pub-title">{{ pub.title }}</h3>

<div class="pub-authors">
{{ pub.excerpt | replace: "Yulin Xu", "<strong>Yulin Xu</strong>" }}
</div>

{% if pub.paperurl and pub.paperurl != "" %}
<div class="pub-links">
<a href="{{ pub.paperurl }}">Paper</a>
</div>
{% endif %}

</div>

{% endfor %}

</section>


<section id="misc" class="home-section">

<h2>Life</h2>

<p>
Outside of research, I enjoy playing tennis and watching professional tennis matches. I closely follow both the ATP and WTA tours and enjoy keeping up with tournaments throughout the season.
</p>

</section>
