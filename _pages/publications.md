---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

> You have the right to work, but for the work's sake only. You have no right to the fruits of work. Desire for the fruits of work must never be your motive in working. Never give way to laziness, either.
Perform every action with you heart fixed on the Supreme Lord. Renounce attachment to the fruits. Be even-tempered in success and failure: for it is this evenness of temper which is meant by yoga.
Work done with anxiety about results is far inferior to work done without such anxiety, in the calm of self-surrender. Seek refuge in the knowledge of Brahma. They who work selfishly for results are miserable.
\- Bhagavad Gita

<p>{{author.googlescholar}}</p>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
