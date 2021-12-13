---
title: In The Troll Pit
---

# In The Troll Pit

A podcast about retro computers and the people who love them.

Episodes:
<% for (const page of pages.filter(p => p.title !== 'In The Troll Pit')) { _%>
* [<%= page.title || pathTo(page) %>](<%= pathTo(page) %>)
<% } _%>

Keep tinkering!