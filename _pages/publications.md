---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my publications on <u><a href="https://scholar.google.com/citations?user=OHU9yzAAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}


<i>Peer-Reviewed Books</i>
======

{% for post in site.peer_reviewed_books reversed %}
  {% include archive-single.html %}
{% endfor %}

<i>Peer-Reviewed Articles</i>
======

{% for post in site.peer_reviewed_articles reversed %}
   {% include archive-single.html %}
{% endfor %}

<i>Non-refereed Publications</i>
======

{% for post in site.non_refereed_publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<i>Work in progress</i>
======

{% for post in site.in_progress reversed %}
  {% include archive-single.html %}
{% endfor %}


{% if false %}
  Book Reviews
  ======
  {% for post in site.book_reviews  reversed %}
    {% include archive-single.html %}
  {% endfor %} 
{% endif %}
