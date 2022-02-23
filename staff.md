---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 10
---

# Staff

## Heads

{% assign instructors = site.staffers | where: 'role', 'Head' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

## Discussion TAs

{% assign staff = site.staffers | where: 'role', 'Discussion TA' %}
<div class="role">
  {% for staffer in staff %}
  {{ staffer }}
  {% endfor %}
</div>

## Lab TAs

{% assign staff = site.staffers | where: 'role', 'Lab TA' %}
<div class="role">
  {% for staffer in staff %}
  {{ staffer }}
  {% endfor %}
</div>


## Readers

{% assign readers = site.staffers | where: 'role', 'Head Reader' %}
<div class="role">
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>

{% assign readers = site.staffers | where: 'role', 'Reader' %}
<div class="role">
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>
