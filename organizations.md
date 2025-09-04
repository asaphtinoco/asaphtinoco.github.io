---
layout: page
title: "Other Organizations"
permalink: /organizations/
---

# Other Organizations

I regularly post new projects in my other organizations. Check them out below:

<ul>
{% for org in site.organizations %}
  <li>
    <strong><a href="{{ org.url }}" target="_blank">{{ org.name }}</a></strong><br>
    {{ org.description }}
  </li>
{% endfor %}
</ul>
