---
layout: page
title: Writings
---

<p>Here you can find various articles by Bhante Sujato and Bhante Akaliko. These are reflections on different aspects of facing up to the climate crisis as it unfolds. Posts with the title “Harbingers” form a loosely-themed series by Bhante Sujato, which includes analytic articles as well as personal reflections and short stories.</p>
  
 <dl class="post-list">
    {% for post in site.posts %}
  <a href="{{ post.url }}">
  <dt>{{ post.title }}</dt>
  <dd>
    <span class="author">{{ post.author }}</span>
    <span class="date">{{ post.date | date: "%-d %B %Y" }}</span>
    <span class="blurb">{{ post.blurb }}</span>
  </dd>
    </a>
    {% endfor %}
</dl> 

