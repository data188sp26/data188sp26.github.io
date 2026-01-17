---
layout: page
title: Calendar (Static)
description: Lecture, Discussion and OH schedules
nav_order: 2
---

# Calendar (Static)

This calendar contains standard weekly course activities, like: lecture, discussion, and office hours.

{% for calendar in site.calendars %}
  {{ calendar }}
{% endfor %}
