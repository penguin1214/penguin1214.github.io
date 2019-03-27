---
layout: page
permalink: /research/
title: Research


------

## Professional service

- Grant proposals{% for review in site.data.cv.reviews.grants %}
    - {{review.title}} {% for y in review.years %} [{% if review.url %}[{{y.year}}]({{review.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}

- Conference reviews{% for review in site.data.cv.reviews.conference %}
    - {{review.title}} {% for y in review.years %} [{% if y.url %}[{{y.year}}]({{y.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}

- Journal reviews{% for review in site.data.cv.reviews.journal %}
    - {{review.title}} {% for y in review.years %} [{% if review.url %}[{{y.year}}]({{review.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}
