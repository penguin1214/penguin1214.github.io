---
layout: page
title: 
permalink: /
---

{% include image.html url="images/profile_1.jpg" caption="" width="250px" align="right" %}
**M.Sc. student**

Department of Electrical & Computer Engineering<br/>
University of California, Santa Barbara



<p>
<br/>
<br/>
</p>

Email: [jingleiyang@ucsb.edu]

------

I am a master student in Department of Electrical & Computer Engineering at University of California, Santa Barbara and working closely with [Prof. Lingqi Yan] on real-time rendering. Before that I received my B.Eng degree in Electronics and Information Engineering from Sichuan University, China, in Jun. 2018, where I worked with [Prof. Wei Wu] on image super-resolution.

My research interest includes physically-based rendering (both real-time and offline) as well as overlapping areas of computer vision and computer graphics.

------

## Education
- M.Sc. in Electrical and Computer Engineering
<br/>
*University of California, Santa Barbara, USA, Sep. 2018 ~ Jun. 2020 (expected)*
- B.Eng in Electronics and Information Engineering
<br/>
*Sichuan University, China, Sep. 2014 ~ Jun. 2018*

------

## Peer reviewed publications

{% assign thumbnail="right" %}

{% for pub in site.data.cv.publications %}
<!-- {% if pub.image %}
{% include image.html url=pub.image caption="" height="80px" align=thumbnail %}
{% endif %} -->
**{{pub.title}}**<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} *{{pub.year}}*  [[paper]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})] {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}

{% endfor %}

[Prof. Lingqi Yan]: http://www.cs.ucsb.edu/~lingqi/
[Prof. Wei Wu]: https://scholar.google.com/citations?user=YPP7Ln4AAAAJ&hl=en
[jingleiyang@ucsb.edu]: mailto:jingleiyang@ucsb.edu
------

## Teaching/Grading

- Grader Spring 2019 CS165B Machine Learning

- TA Fall 2016 Digital Circuits