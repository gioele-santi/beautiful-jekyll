---
layout: page
title: About me
subtitle: Some extra information about me
---

{% capture override_title %}{% t global.about %}{% endcapture %}
{% capture override_subtitle %}{% t global.about_subtitle %}{% endcapture %}

{% tf aboutme.md %}