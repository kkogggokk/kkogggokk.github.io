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
    <a href="mailto:{{site.email}}" title="email">
    <i class="fa fa-envelope-o" aria-hidden="true"></i>E-mail</a>
</li>
<li>
    <a href="https://github.com/{{site.github_username}}" title="GitHub"><i class="fa fa-github" aria-hidden="true"></i>GitHub</a>
</li>
<li>
   <a href="https://www.linkedin.com/in/{{site.linkedIn_username}}" title="LinkedIn"><i class="fa fa-linkedin" aria-hidden="true"></i>LinkedIn</a>
</li>
<li>
    <a href="https://twitter.com/{{site.twitter_username}}" title="Twitter"><i class="fa fa-twitter" aria-hidden="true"></i>Twitter</a>
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
<<<<<<< HEAD
        <li>🧑‍💻 Ahnlab Software QA Trainee</li>
=======
        <li>🧑‍💻 Ahnlan Software QA Treinee</li>
>>>>>>> parent of 7e82c4f... update
        <li>🧑‍💻 Security pentest consultant</li>
        <li>🏆 Engineer Information Processing</li>
        <li>🏆 CCPG</li>
        <li>⚙️ Web & Mobile Pentest</li>
        <li>⚙️ Python</li>
        <li>...</li>
      </ul>
    </div>
  </div>
  
# Likes 
<div class="about-content-right">
    <!-- <h2><i class="far fa-thumbs-up fa-fw"></i> Likes</h2> -->
    <ul>
    <li>🏋️‍♀️ Exercise</li>
    <li>🐱 Cat</li>
    <li>⛱ Travel</li>
    </ul>
</div>
