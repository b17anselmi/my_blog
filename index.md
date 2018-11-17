---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
---
<div >
  {% for post in site.posts %}
  <div class="post">
      <h3>
          <a href="{{ post.url }}">{{ post.title }}</a>
      </h3>
        <div class="date">{{post.date}}</div>
  </div>
  {% endfor %}
</div>
