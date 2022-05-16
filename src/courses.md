---
layout: course
title: Courses
---
<div class="columns">
  <div class="column is-11">
    <ul>
      <% collections.courses.resources.each do |course| %>
        <li>
          <p class="is-italic has-text-weight-light"><%= course.data.volume %></p>
        </li>
        <li>
          <h5 class="title is-5"><a href="<%= course.relative_url %>"><%= course.data.name %></a></h5>
        </li>
        <li>
          <p>&nbsp;</p>
        </li>
      <% end %>   
    </ul>
  </div>
  <div class="column is-1">
    <ul>
      <% collections.courses.resources.each do |course| %>
        <li>
          <p>&nbsp;</p>
        </li>
        <li>
          <p class="has-text-weight-bold"><%= course.data.annotation %></p>
        </li>
        <li>
          <p>&nbsp;</p>
        </li>
      <% end %>  
    </ul>
  </div>  
</div>
