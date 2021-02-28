---
layout: page
title: About
permalink: /about/
icon: heart
type: page
---

* content
{:toc}







<div class="about">
  <div class="about-profile">
    <div class="about-profile-image">
      <img src="https://raw.githubusercontent.com/kkogggokk/kkogggokk.github.io/master/_assets/img/_SIG_kkogggokk.png" alt="kkogggokk">
      <!-- <div>&copy;kkogggokk</div> -->
    </div>
</div>

<div class="about-profile-content">
    <!-- <h2><span>수정중</span> KKKKK<span>u</span> GGG</h2> -->
<p>
dfdfdf분야를 가리지 않는 <b>잡식성</b> 개발자 <i class="fas fa-robot fa-fw"></i><br>
<span class="whisper">ddddd<i class="far fa-smile fa-fw"></i>)</span>
</p>
<p>
개발 관련 글을 자유롭게 올립니다.ddd
</p>

<div class="about-profile-content-contacts">
<li>
    <i class="fas fa-map-marker-alt fa-fw"></i>
    <span>Seoul, Republic of Korea</span>
</li>
<li>
    <a href="mailto:{{site.email}}" title="email"><i class="fa fa-envelope-o" aria-hidden="true"></i></a>
</li>
<li>
    <a href="{{ site.social.links[0] }}" target="_blank">
    <i class="fab fa-github fa-fw"></i>
    <span>GitHub</span>
    </a>
</li>
<li>
    <a href="{{ site.social.links[1] }}" target="_blank">
    <i class="fab fa-linkedin fa-fw"></i>
    <span>LinkedIn</span>
    </a>
</li>
<li>
    <a href="{{ site.social.links[2] }}" target="_blank">
    <i class="fab fa-twitter fa-fw"></i>
    <span>Twitter</span>
    </a>
</li>
</div>
</div>
  </div>

<!-- Include the library. -->
<script
  src="https://unpkg.com/github-calendar@latest/dist/github-calendar.min.js"
></script>

<!-- Optionally, include the theme (if you don't want to struggle to write the CSS) -->
<link
   rel="stylesheet"
   href="https://unpkg.com/github-calendar@latest/dist/github-calendar-responsive.css"
/>

<div>
    <!-- Prepare a container for your calendar. -->
    <!-- <div style="text-align: center;"><strong>나의 GitHub Contribution 그래프</strong></div> -->
    <div class="calendar">
        <!-- Loading stuff -->
        Loading data ...
    </div>
</div>

<script>
    GitHubCalendar(".calendar", "kkogggokk", { responsive: true, tooltips: false, global_stats: false}).then(function() {
        // delete the space underneath the module bar which is caused by minheight 
        document.getElementsByClassName('calendar')[0].style.minHeight = "100px";
        // hide more and less legen below the contribution graph
        document.getElementsByClassName('contrib-legend')[0].style.display = "none";
    });
</script>

# Experiences 
  <div class="about-content">
    <div class="about-content-left">
      <!-- <h2><i class="fas fa-hat-wizard fa-fw"></i> Experiences</h2> --> 
      <ul>
        <li>🧑‍🎓 Gachon Univ. Computer Science</li>
        <li>🧑‍💻 Ahnlan Software QA Treinee</li>
        <li>🧑‍💻 Security pentest consultant</li>
        <li>🏆 Engineer Information Processing</li>
        <li>🏆 CCPG</li>
        <li>🪄 Web & Mobile Pentest</li>
        <li>🪄 Python</li>
        <li>...</li>
      </ul>
    </div>
  </div>
  
# Likes 
<div class="about-content-right">
    <!-- <h2><i class="far fa-thumbs-up fa-fw"></i> Likes</h2> -->
    <ul>
    <li>🏋️‍♀️ Exercise : Pilates, Fitness, Bicycle, Surfing, Snowboarding</li>
    <li>🐱 Cat : Korean Shorthair cat cheese tabby - Hob[호비]</li>
    <li>📖 Knowledge about Everything</li>
    <li>⛱ Travel</li>
    </ul>
</div>
