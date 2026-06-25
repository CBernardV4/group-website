---
layout: default
---

This is to make sure that the navigation set-up works?

Here are some random names of people that have not worked in any sort of project.
This is just to ensure that the layout works nicely.

{% for team_member in site.team_members %}
- {{ team_member.name }}. **Joined on** {{ team_member.start_date}}
  - Role: {{ team_member.role | capitalize }}
{% endfor %}
<!-- Comment here -->
