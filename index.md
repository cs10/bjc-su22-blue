---
layout: home
title: Home
nav_exclude: false
nav_order: 1
---

<script src="assets/jquery.min.js"></script>
<script src="assets/dayjs.min.js"></script>
<script>
  !function(e,t){"object"==typeof exports&&"undefined"!=typeof module?module.exports=t():"function"==typeof define&&define.amd?define(t):(e="undefined"!=typeof globalThis?globalThis:e||self).dayjs_plugin_weekOfYear=t()}(this,(function(){"use strict";var e="week",t="year";return function(i,n,r){var f=n.prototype;f.week=function(i){if(void 0===i&&(i=null),null!==i)return this.add(7*(i-this.week()),"day");var n=this.$locale().yearStart||1;if(11===this.month()&&this.date()>25){var f=r(this).startOf(t).add(1,t).date(n),s=r(this).endOf(e);if(f.isBefore(s))return 1}var a=r(this).startOf(t).date(n).startOf(e).subtract(1,"millisecond"),o=this.diff(a,e,!0);return o<0?r(this).startOf("week").week():Math.ceil(o)},f.weeks=function(e){return void 0===e&&(e=null),this.week(e)}}}));
</script>
<script src="assets/schedule.js"></script>

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
