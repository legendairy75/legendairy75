---
layout: default
title: Home
---
Something.42
{% capture readme_content %}{% include_relative README.md %}{% endcapture %}
{{ readme_content | markdownify }}
