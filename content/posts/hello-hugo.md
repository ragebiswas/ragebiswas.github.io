---
title: "Hello Hugo"
date: 2020-08-22T16:44:13+05:30
draft: true
---

# Hello

So I've been meaning to revive my blog in a while, and instead of trying to bring up the old version (based on [Ghost](https://www.ghost.org)), I've decided to give [Hugo](https://gohugo.io) a shot since static site generators are so well suited for occasional bloggers such as me, who post once in a decade or so.

This post is meant to try out basic formatting of the [Ananke](https://github.com/theNewDynamic/gohugo-theme-ananke) theme.

# Markdown

As a programmer, Markdown is what I prefer for blog posts and it's delightful that Hugo supports this out of the box and is fairly optimized for this.

# Basic Text

Should support, at minimum, decent rendering of bullets:
* Non-numeric bullets
   * With indentation

1. Numeric bullets
   1. With sub-bullets
   1. And more
1. And more

And quoting:

> That's what she said!

And usual *text* **shenanigans**.

# Code Snippets

The other thing a programmer blog should support is neat code snippets, again built into Hugo. Here are a couple of attempts:

### Python

```python
import os
import this
```

### Java

```java
System.out.println("Hello Hugo")
```

# Images

Apart from text, we might need basic support for inline images. Here's a try at one:

![Hugo Logo](/images/hugo-logo.svg)

# Commenting System

Finally, this blog should support basic Disqus commenting, another built-in feature of Hugo. The astute reader may have observed that my choice of blogging platform was based on how little work I had to do myself.