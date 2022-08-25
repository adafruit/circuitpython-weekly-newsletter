---
title: Adafruit CircuitPython Weekly Newsletter
---

## Drafts

{% assign sorted = site.drafts | sort: 'date' | reverse %}
{% for draft in sorted %}
[{{ draft.title }}]({{ draft.url | absolute_url }})
{% endfor %}

## Archive


Older items that have been moved to "attic" are not rendered here.
This is needed to keep the update time for github pages reasonable.
The canonical site for the archives is
[https://www.adafruitdaily.com/category/circuitpython/](https://www.adafruitdaily.com/category/circuitpython/)

{% for post in site.posts%}
[{{ post.title }}]({{ post.url | absolute_url }})
{% endfor %}
