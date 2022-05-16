---
layout: module
title: Units
---

<ul>
  <% collections.modules.resources.each do |unit| %>
    <li>
      <a href="<%= unit.relative_url %>"><%= unit.data.title %></a>
    </li>
  <% end %>
</ul>
