---
layout: default
title: "Welcome to my blog"
permalink: :basename
---

Welcome to My Home Page

{% assign date = '2020-04-13T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}

I'm glad you are here. I plan to talk about ...

- CTF's
- cybersecurity
- Technology

{% include 01-name.md %}

</br>

{% include 02-image.md %}

</br>

{% include 03-links.md %}