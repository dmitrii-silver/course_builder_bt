---
layout: course
title: Courses
---
<div class="content">
  <% collections.courses.resources.each do |course| %>
    <table class="table is-fullwidth">
      <tbody>
        <tr>
          <td>
            <p class="is-italic has-text-weight-light"><%= course.data.volume %></p>
            <h5 class="title is-5"><a href="<%= course.relative_url %>"><%= course.data.name %></a></h5>
          </td>
          <td>
            <p>&nbsp;</p>
            <div class="level-right">
              <p class="has-text-weight-bold"><%= course.data.annotation %></p>
            </div>
          </td>
        </tr>
      </tbody>
    </table>
  <% end %>
</div>
