---
layout: page
title: Blogposts
permalink: /Blogposts/
---

<div class="home">

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span id="{{ post.title }}" class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>

      </li>
    {% endfor %}
  </ul>

</div>