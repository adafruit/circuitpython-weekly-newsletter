---
title: Adafruit CircuitPython Weekly Newsletter
---

## Drafts

{% assign sorted = site.drafts | sort: 'date' | reverse %}
{% for draft in sorted %}
[{{ draft.title }}]({{ draft.url | absolute_url }})
{% endfor %}

## Archive


The previous years' content has been moved to the [circuitpython-weekly-newsletter-archives](https://github.com/adafruit/circuitpython-weekly-newsletter-archives) repository, and is not rendered here.
This is needed to keep the update time for Github Pages and the size of this repo reasonable.
The canonical site for the newsletter archives is
[https://www.adafruitdaily.com/category/circuitpython/](https://www.adafruitdaily.com/category/circuitpython/).

{% for post in site.posts%}
[{{ post.title }}]({{ post.url | absolute_url }})
{% endfor %}
