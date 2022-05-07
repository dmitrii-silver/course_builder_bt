---
layout: course
title: Courses
---

<ul>
  <% collections.courses.resources.each do |course| %>
    <li>
      <a href="<%= course.relative_url %>"><%= course.data.title %></a>
    </li>
  <% end %>
</ul>
