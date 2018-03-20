---
title: Adafruit CircuitPython Weekly Newsletter
---

## Drafts

    {{ site.posts | jsonify }}
{% assign sorted = site.drafts | sort: 'date' | reverse %}
{% for draft in sorted %}
[{{ draft.title }}]({{ draft.url }})
{% endfor %}

## Archive

{% for post in site.posts%}
[{{ post.title }}]({{ post.url }})
{% endfor %}
