---
layout: page
title: 三天打鱼，两天晒网
tagline: 每天的心情要好
---
{% include JB/setup %}

时不时在这里抒发一下自己的感情，记录一点心得。


```
public static void main(String[] args){
	System.out.println("hello world!");
}
```


### 文章列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




