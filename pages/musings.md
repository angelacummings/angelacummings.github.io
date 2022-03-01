---
title: Musings
permalink: /musings
class: wide
summary: A list of musings and observations by Angela Cummings.
preserve-headings: true
---

{%- assign sortedNotes = site.musings | sort: 'written' | reverse %}
{%- for note in sortedNotes -%}
{% include snippet.html full=true %}
{%- endfor -%}
