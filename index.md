---
layout: single
toc: false
sidebar: 
   nav: "index"
author_profile: false
read_time: false
comments: false
share: false
related: false
---

# Marketing and Recruitment Style Guide

Entries in this style guide are copied or adapted from The University of Alabama Strategic Communications Editorial Style Guide (Summer 2017 and subsequent versions)[^1] and the Associated Press Stylebook, and modified based on Marketing and Recruitment house style. Many examples in this guide are directly from those sources. The AP Stylebook also references Webster’s New World College Dictionary.

Entry sources are cited when available. Content on the AP Stylebook website may be viewed through [UA Libraries](http://libdata.lib.ua.edu/login?url=https://www.apstylebook.com/ua_edu).

[^1]: The University of Alabama Strategic Communications Editorial Style Guide is available at [https://strategiccommunications.ua.edu/standards/editorial-style](https://strategiccommunications.ua.edu/standards/editorial-style). The Strategic Communications online guide is constantly updated, and references in this document may no longer appear on the Strategic Communications webpage.


## Table of Contents

- [Grammar/Punctuation](#grammarpunctuation)
- [Word Choice](#word-choice)
- [Marketing and Recruitment Customs](#marketing-and-recruitment-customs)
- [References and Resources](#references-and-resources)
- [Site Index](siteindex)

### Grammar/Punctuation
<ul class="index_toc">
{% assign filtered_posts = site.pages | where: 'section', 'grammar' %}
{% for entry in filtered_posts %}
  <li><a href="{{ entry.url | absolute_url }}">{{ entry.title}}</a></li>
{% endfor %}
</ul>

### Word Choice
<ul class="index_toc">
{% assign filtered_posts = site.pages | where: 'section', 'wordchoice' %}
{% for entry in filtered_posts %}
  <li><a href="{{ entry.url | absolute_url }}">{{ entry.title}}</a></li>
{% endfor %}
</ul>

### Marketing and Recruitment Customs
<ul class="index_toc">
{% assign filtered_posts = site.pages | where: 'section', 'customs' %}
{% for entry in filtered_posts %}
  <li><a href="{{ entry.url | absolute_url }}">{{ entry.title}}</a></li>
{% endfor %}
</ul>

## References and Resources
<ul class="index_toc">
{% assign filtered_posts = site.pages | where: 'section', 'references' %}
{% for entry in filtered_posts %}
  <li><a href="{{ entry.url | absolute_url }}">{{ entry.title}}</a></li>
{% endfor %}
</ul>