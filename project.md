---
layout: page
title: Projects
permalink: /project/
nav: true
---
{% for project in site.projects reversed %}
* [{{project.title}}]({{site.baseurl}}{{project.url}}){% endfor %}
