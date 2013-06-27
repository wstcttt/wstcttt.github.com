---
layout: page
category : test
title : Test Page
tagline: "Supporting tagline"
tags : [hehe, test]
---
{% include JB/setup %}

Here is the first line.

## 标题一 

> test hehehehehhehe 
>   
>     int a, *b;
>     char max;
>     if(hehe)
>     	printf();
>     else
>     	hahahaha;

this is code:

    cococococococo;
    fuccccccccckkkkkk;
code end.

下面是分割线

***

haha

*****

hehe

---

This is [百度的网址] [1] 能打开不？
[1]: http://baidu.com  "没错！这就是百度！"

[Google][]
[Google]: http://google.com "GooGGGGGG"

### 标题2


![这是一只喵][2]
[2]: /img/miao.jpg "喵星人！！！"


标题二里面的正文！！

### 标题2.1

标题2.1里面的正文！！

### 标题2.2

标题2.2里面的正文！！


**这是格式1**

- 这是格式2
- 这是格式2

# 标题

 _这是格式3_

__strong__

*hehe*

页面路径： [页面文字](/index.html#start-now)

这是个神马：

- **\_需要转义**  
	这是正文.

- **一个小标题**  
	`这是高亮显示的`

这是超链接: <https://github.com/mojombo/jekyll/wiki/Usage>


后面显示的文字带超链接： [我是文字](https://github.com/mojombo/jekyll/wiki/YAML-Front-Matter)

Example:

    ---
    title :  Hello World
    categories : [lessons, beginner]
    ---

这是个神马格式:

    .
    |-- people
        |-- bob
            |-- essay.html

难道是冒号:
{% capture text %}...
<body>
  <div id="sidebar"> ... </div>
  <div id="main">
    |.{content}.|
  </div>
</body>
...{% endcapture %}
{% include JB/liquid_raw %}

试试:
{% capture text %}fuck 你妹妹
{% endcapture %}
{% include JB/liquid_raw %}

**Thank you** for reading this far.


Please take a look at [{{ site.categories.api.first.title }}]({{ BASE_PATH }}{{ site.categories.api.first.url }}) 
or jump right into [Usage]({{ BASE_PATH }}{{ site.categories.usage.first.url }}) if you'd like.
