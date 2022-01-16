---
layout: home
title: Home
nav_exclude: true
---

# **CS 10: The Beauty and Joy of Computing**
{: .mb-2 }
UC Berkeley, Spring 2022
{: .mb-2 .fs-6 .text-grey-dk-100 }

{{ site.description }}
{: .mb-2 .fs-5 }

**Instructor:** Michael Ball
{: .fs-4 }

{% if site.announcements %}
  {{ site.announcements.last }}
  [Previous Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

![Alonzo](./assets/images/alonzo.png)

{% include_relative calendar.md %}
