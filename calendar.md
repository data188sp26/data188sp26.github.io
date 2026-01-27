---
layout: page
title: Calendar
description: Lecture, Discussion and OH schedules
nav_order: 2
---

# Calendar

This calendar contains standard weekly course activities, like: lecture, discussion, and office hours.

{% for calendar in site.calendars %}
  {{ calendar }}
{% endfor %}
