---
layout: unit
title: Units
---

<ul>
  <% collections.units.resources.each do |unit| %>
    <li>
      <a href="<%= unit.relative_url %>"><%= unit.data.title %></a>
    </li>
  <% end %>
</ul>
