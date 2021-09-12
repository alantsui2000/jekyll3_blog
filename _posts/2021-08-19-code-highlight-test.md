---
layout: post
title: "代码高亮测试"
date: 2021-08-20 00:29:28 +0800
categories: tech test
author: ouyang
---

## highlight 模板标签

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
{% endhighlight %}

## kramdown 原生支持的高亮语法

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
```

## 测试过度解析

{% raw %}
```
User Name: {{ user.username }}
Password: {{ user.password }}
```
{% endraw %}

{% raw %}
User Name: {{ user.username }}<br>
Password: {{ user.password }}
{% endraw %}
