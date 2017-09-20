---
layout: page
title:
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## About Me

I'm currently a Computer Modelling and Data Analytics (CMDA) student at Virginia Tech. I spent 3 and a half years in the Computer Science program here before switching to CMDA, which is a pretty new program at Tech. 
</div>
