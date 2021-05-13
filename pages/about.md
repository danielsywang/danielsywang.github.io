---
layout: page
title: About
description: 书生的个人博客
keywords: danielsywang, 书生
comments: true
menu: 关于
permalink: /about/
---

　　本人具有数学+管理+软件工程的教育背景，具有投资、IT和教育三大领域的丰富工作经验。担任过程序员、主管、教师、大型企业的中层管理者、教育机构的创始人、投资公司的合伙人等职务，目前主要关注机器学习和深度学习。希望与各位同行一同学习，一同进步！


## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'mazhuang.org' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/qrcode.jpg" alt="闷骚的程序员" />
</li>
{% endif %}
</ul>


## 专业技能

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
