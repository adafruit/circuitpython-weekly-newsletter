---
title: Adafruit CircuitPython Weekly Newsletter
---

## Drafts

{% assign sorted = site.drafts | sort: 'date' | reverse %}
{% for draft in sorted %}
[{{ draft.title }}]({{ draft.url | absolute_url }})
{% endfor %}

## Archive

{% for post in site.posts%}
[{{ post.title }}]({{ post.url | absolute_url }})
{% endfor %}
