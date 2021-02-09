---
layout: page
title: About
permalink: /about/
icon: heart
type: page
---

* content
{:toc}

## test

<!-- <iframe src="https://githubbadge.appspot.com/gaohaoyang?s=1" style="border: 0;height: 142px;width: 200px;overflow: hidden;" frameBorder="0"></iframe> -->

<!-- Include the library. Github calendar --> 
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
    <div style="text-align: center;"><strong>My GitHub Contribution </strong></div> 
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

## test2

* GitHub：[Gaohaoyang](https://github.com/Gaohaoyang)
* email：gaohaoyang126@126.com
* [Weibo](http://weibo.com/3115521wh)
* [知乎](https://www.zhihu.com/people/gaohaoyang)
* [Facebook](https://www.facebook.com/gaohaoyang.water)
* [豆瓣](https://www.douban.com/people/42525035/)
* [豆瓣音乐人-浩阳的小站](https://site.douban.com/haoyangaiyinyue/)


## test1

[羡辙杂俎](http://zhangwenli.com/blog) \| [Anotherhome](https://www.anotherhome.net) \| [Reverland](http://reverland.org/) \| [ZhiLi](http://lizhipower.github.io/) \| [Simmer](http://simmer-jun.github.io/) \| [awthink](http://awthink.net/) \| [Aralic](http://aralic.github.io/) \| [zchen9](http://www.chen9.info/) \| [wuhuaji](http://wuhuaji.me/) \| [lisheng](http://www.lishengcn.cn/) \| [薛彬XueBin](http://axuebin.com/blog/) \| [TBOOX](http://www.tboox.org/cn/) \|  [Ling](http://linglinyp.com/)

## Comments

{% include comments.html %}
