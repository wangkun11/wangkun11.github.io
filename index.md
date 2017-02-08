---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>王坤</h1>
        <h2>2015-2018 华中科技大学 武汉光电国家实验室 研究生 </h2>
        <h2>2011-2015 武汉理工大学 计算机科学与技术学院 本科 </h2>
        <h2>2013-2015 武汉大学 管理学院 双学位 </h2>
        <a href="http://weibo.com/u/2704327061/" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://www.douban.com/people/kingformyself/" target="_blank"><img src="http://www.douban.com/favicon.ico" alt="" width="22"/></a>
        <a href="http://instagram.com" target="_blank"><img src="http://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="22"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
