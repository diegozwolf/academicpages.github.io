---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<h2><i>Peer-Reviewed Books</i></h2>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.peer_reviewed_books reversed %}
  
  {% include archive-single.html %}
{% endfor %}

<h2><i>Peer-Reviewed Articles</i></h2>

{% for post in site.peer_reviewed_articles %}
   {% include archive-single.html %}
{% endfor %}

<h2><i>Non-refereed Publications</i></h2>

{% for post in site.non_refereed_publications %}
  {% include archive-single.html %}
{% endfor %}

<h2><i>Work in progress</i></h2>

{% for post in site.in_progress %}
  {% include archive-single.html %}
{% endfor %}

<!-- <h2><i>Book Reviews</i></h2>
{% for post in site.book_reviews %}
  {% include archive-single.html %}
{% endfor %} -->
