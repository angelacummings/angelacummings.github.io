---
permalink: /poems
class: wide
lede: true
---

*Sing all the silenced songs furled inside your heart's sharp memory, for you are a choir that magically assembles, but briefly and only once.*

# List of poems

{%- for note in site.poems -%}
  {% include snippet.html %}
{%- endfor -%}
