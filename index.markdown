---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
nav_exclude: true
---

Welcome to the **National Integrated General Electronic Ledger** technical blog.

Here you'll find project updates, technical articles, and insights related to our ongoing work.

**Posts:**
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>

Stay tuned for regular updates and in-depth discussions on our development process and technology choices.
