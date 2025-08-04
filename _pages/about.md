---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm an incoming PhD student from [University of Southern California](https://www.usc.edu), advised by [Corey E. Baker](https://viterbi.usc.edu/directory/faculty/Baker/Corey). My research interests include machine learning methods and their applications in recommendation systems and autonomous systems.

I am passionate about exploring a wide range of applications in machine learning, particularly those that address real-world problems. I enjoy discussing ideas, asking questions, and thinking deeply about complex systems. Please contact me directly if interested!

[Email](mailto:yulinxu@usc.edu)/ [Wechat](../images/wechat.jpg)

<h2><strong><span style="color:red">News</span></strong></h2>
<ol id="news-list">
  <li><strong><span style="color:red">News 1:</span></strong> One paper accepted to KDD 2025!</li>
  <li><strong><span style="color:red">News 2:</span></strong> Internship at Tencent starts July 2025.</li>
  <li><strong><span style="color:red">News 3:</span></strong> Invited to serve as KDD 2026 reviewer.</li>
  <li class="hidden"><strong><span style="color:red">News 4:</span></strong> Finished my Master's at UCI.</li>
  <li class="hidden"><strong><span style="color:red">News 5:</span></strong> New preprint on ArXiv!</li>
</ol>

<button id="toggle-button" onclick="toggleNews()">Show More</button>

<style>
  .hidden {
    display: none;
  }
</style>

<script>
  function toggleNews() {
    const hiddenItems = document.querySelectorAll("#news-list .hidden");
    const button = document.getElementById("toggle-button");
    const isHidden = hiddenItems[0].style.display === "none";

    hiddenItems.forEach(item => {
      item.style.display = isHidden ? "list-item" : "none";
    });

    button.innerText = isHidden ? "Show Less" : "Show More";
  }
</script>



