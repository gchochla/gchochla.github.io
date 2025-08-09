---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

> You have the right to [a paper], but for the [paper]'s sake only. You have no right to the [publication] of [a paper]. Desire for the [publication] must never be your motive in working. Never give way to laziness, either.
Perform every action with you heart fixed on the Supreme Lord. Renounce attachment to [publication]. Be even-tempered in success and failure: for it is this evenness of temper which is meant by yoga.
[A paper] done with anxiety about [publication] is far inferior to [a paper] done without such anxiety, in the calm of self-surrender. Seek refuge in the knowledge of Brahma. They who work selfishly for [publication] are miserable.
\- Bhagavad Gita

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
