---
layout: single
classes: wide
toc: false
sidebar: 
   nav: "index"
author_profile: false
read_time: false
comments: false
share: false
related: false
---

# Marketing Style Guide

Entries in this style guide are copied or adapted from The University of Alabama Strategic Communications Editorial Style Guide (Summer 2017 and subsequent versions)[^1] and the Associated Press Stylebook, and modified based on Marketing house style. Many examples in this guide are directly from those sources. The AP Stylebook also references Webster’s New World College Dictionary.

Entry sources are cited when available. Content on the AP Stylebook website may be viewed through [UA Libraries](http://libdata.lib.ua.edu/login?url=https://www.apstylebook.com/ua_edu).

[^1]: The University of Alabama Strategic Communications Editorial Style Guide is available at [https://strategiccommunications.ua.edu/standards/editorial-style](https://strategiccommunications.ua.edu/standards/editorial-style). The Strategic Communications online guide is constantly updated, and references in this document may no longer appear on the Strategic Communications webpage.

{% assign toc = site.data.navigation.index | where: 'title', 'Contents' | first %}
## {{toc.title}}
<ul>
{% for entry in toc.children %}
<li><a href="{{entry.url}}">{{entry.title}}</a></li>
{% endfor %}
</ul>

## Feature Wrapper

<div class="feature__wrapper" markdown="1">
   
   {% include section_toc.html section="References and Resources" %}
   
   {% include section_toc.html section="Grammar/Punctuation" %}
   
   {% include section_toc.html section="Word Choice" %}
   
   {% include section_toc.html section="Marketing Customs" %}

</div>