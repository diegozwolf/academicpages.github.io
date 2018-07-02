---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u> <a href="{{author.googlescholar}}">my Google Scholar profile</a>. </u>
{% endif %}

{% include base_path %}

Peer Reviewed Books
======

{% for post in site.peer_reviewed_books %}
  {% include archive-single.html %}
{% endfor %}

Peer Reviewed Articles
======

{% for post in site.peer_reviewed_articles %}
   {% include archive-single.html %}
{% endfor %}

Non-refereed Publications
======

{% for post in site.non_refereed_publications %}
  {% include archive-single.html %}
{% endfor %}

Work in progress
======

{% for post in site.in_progress %}
  {% include archive-single.html %}
{% endfor %}


{% if false %}
  Book Reviews
  ======
  {% for post in site.book_reviews %}
    {% include archive-single.html %}
  {% endfor %} 
{% endif %}