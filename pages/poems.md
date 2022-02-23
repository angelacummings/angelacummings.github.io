---
permalink: /poems
class: wide
lede: true
preserve-headings: true
---

*Sing all the silenced songs furled inside your heart's sharp memory, for you are a choir that magically assembles, but briefly and only once.*

<h1>Poems</h1>

{%- for note in site.poems -%}
  {%- include snippet.html poem=true -%}
{%- endfor -%}
