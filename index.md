---
layout: default
title: "蒸汽与魔法"
---

# Tomorrow You Start Building Tomorrow

Per my personal experience, Medium is no longer a great place to host blogs/essays. 

And considering the local-first requirements, now I will use jekyll for my personal website. 

Will try to migrate history essays I thought valuable manually. Now you could still read them from my [Medium](https://medium.com/@xuwenhao).

## Recent Posts

<ul>
{% for post in site.posts reversed limit:5 %}
  <li>
    <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

## Articles

* [Essays](essays)
* [History Articles @ Medium](https://medium.com/@xuwenhao)
* AI炼金术 @ 公众号

## Podcasts

* [AI炼金术 @ 小宇宙](https://www.xiaoyuzhoufm.com/podcast/63e9ef4de99bdef7d39944c8)

## Online Courses

* [AI大模型之美](https://time.geekbang.org/column/intro/100541001)
* [大数据经典论文解读](https://time.geekbang.org/column/intro/100091101)
* [深入浅出计算机组成原理](https://time.geekbang.org/column/intro/100026001)