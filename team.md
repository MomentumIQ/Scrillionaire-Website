---
layout: team
title: Team
---
# Team

{% for teammate in site.team %}
## [{{ teammate.name }}]({{ teammate.url }})
## {{ teammate.position }}

{{ teammate.content | markdownify }}
{% endfor %}