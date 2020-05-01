---
layout: page
title: Math Courses
image: '/images/pages/about.jpeg'
---

So ya like math. It's very satisfying, but you don't know what all those intimidating course numbers nor math fields are about? This is the page for you.

<div class='o-wrapper'>
  <div class='o-grid'>
    {% for post in paginator.posts %}
      {% if 'math' in post.tags%}
        {% include post-card.liquid %}
    {% endfor %}
  </div>

  <div class='o-grid'>
    {% include pagination.html %}
  </div>
</div>