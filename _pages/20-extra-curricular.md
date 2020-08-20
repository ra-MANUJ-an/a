---
layout: page
permalink: /teaching/
title: extra-curricular
content:


service:
-  
    content: Student Mentor for ACL 2020 Student Research Workshop (SRW)
-
    content: Program Committee Member for ACL (2018, 2019, 2020)
-
    content: Program Committee Member for NAACL (2018, 2019)
-
    content: Program Committee Member for EMNLP (2018, 2019, 2020)
-
    content: Program Committee Member for AAAI (2017, 2018)
-
    content: Program Committee Member for EACL 2017
-
    content: Program Committee Member for MRQA Workshop (2018, 2019)
-
    content: Program Committee Member for AKBC (2019, 2020)

teaching:
    - type: record
      date: Spring 2020
      content: "Guest Lecture on Neural Module Networks in CIS 700 - Reasoning for Natural Language Understanding"
      url: "https://www.seas.upenn.edu/~cis700dr/Spring20/"
    - type: record
      date: Fall 2019
      content: "Guest Lectures on Neural Networks in CIS 519 - Applied Machine Learning"
      url: "https://www.seas.upenn.edu/~cis519/fall2019/"
      lecture1: https://youtu.be/G4JROrvOrVM
      lecture2: https://youtu.be/K8NZD_feD0M
    - type: record
      date: Spring 2018
      content: "Guest Lecture on Hidden Markov Models in CIS 530 - Computational Linguistics"
      url: "http://computational-linguistics-class.org/"
    - type: record
      date: Spring 2019
      content: "Teaching Assistant for CIS 700 - Common-sense Reasoning"
      url: "https://www.seas.upenn.edu/~cis700dr/Spring19/"
    - type: record
      date: Spring 2018
      content: "Teaching Assistant for CIS 530 - Computational Linguistics"
      url: "http://computational-linguistics-class.org/"
---

<div class="section">
<h2> Teaching </h2>
<table>
{% for item in page.teaching %}
  <tr>
    <td style="vertical-align: middle;">{{ item.date }}</td>
    <td style="vertical-align: top;" class="announcement">
        {% if item.url %}
            <a class="news-title" href="{{ item.url }}" target="_blank">{{ item.content }}</a>
        {% else %}
            {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
        {% endif %}
        <br>
        {% if item.lecture1 %}
            [<a class="news-title" href="{{ item.lecture1 }}" target="_blank">Lecture 1</a>]
        {% endif %}
        {% if item.lecture2 %}
            [<a class="news-title" href="{{ item.lecture2 }}" target="_blank">Lecture 2</a>]
        {% endif %}
    </td>
  </tr>
{% endfor %}
</table>
</div>


<div class="section">
<h2> Academic Service </h2>
<ul>
{% for item in page.service %}
<li> {{ item.content }} </li>
{% endfor %}
</ul>
</div>
