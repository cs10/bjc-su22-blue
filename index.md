---
layout: home
title: Home
nav_exclude: false
nav_order: 1
---

# **CS 10: The Beauty and Joy of Computing**
{: .mb-2 }
UC Berkeley, Spring 2022
{: .mb-2 .fs-6 .text-grey-dk-100 }

{{ site.description }}
{: .mb-2 .fs-5 }

**Instructor:** Michael Ball
{: .fs-4 }

<div class="d-flex">  <!-- TODO: put alonzo on the right handside -->
  <div class="flex-justify-start" style="flex-grow: 1">
  {% if site.announcements %}
    {{ site.announcements.last }}
  {% endif %}
  </div>
  <div class="float-right">
    <img src="/sp22/assets/images/alonzo.png" alt="Alonzo, the CS10 Mascot" />
  </div>
</div>
<div style="flex-grow: 0">
  <a href="/announcements" class="btn btn-outline">Previous Announcemnts</a>
</div>

## CS10 Calendar

{% include_relative calendar.md %}
