---
title: Testing GitHub Flavored Markdown
date: 2015-10-10 19:37:30 Z
categories:
- jekyll
layout: post
---

These are cheat codes for creating beautiful article with GFM (Github Flavored Markdown).
For more information about GFM, [click here](https://help.github.com/articles/github-flavored-markdown/).

##### # Links

Example :

[click here](https://github.com/remisharrock).

GFM :

```
[click here](https://github.com/remisharrock)
```


##### # italic

Example :

*this is italic !*

GFM :

```
*this is italic !*
```


##### # bold

Example :

**this is bold !**

GFM :

```
**this is bold !**
```


##### # List

Example :

* Item 1
* Item 2
* Item 3

GFM :

```
* Item 1
* Item 2
* Item 3
```


##### # code

Example :

```
function hello(){
	GFM "Hello World!";
}
```

GFM :

{% highlight text %}
```
function hello(){
	GFM "Hello World!";
}
```
{% endhighlight %}


##### # code (inline)

Example :

`echo "Hello World!";`

GFM :

````
`echo "Hello World!";`
````


##### # code (with highlight)

Example :

{% highlight javascript %}
function hello(){
	GFM "Hello World!";
}
{% endhighlight %}

GFM :

{% highlight text %}
{%raw%}
{% highlight javascript %}
function hello(){
	GFM "Hello World!";
}
{% endhighlight %}
{%endraw%}
{% endhighlight %}
