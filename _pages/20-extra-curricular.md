---
layout: page
permalink: /teaching/
title: extra-curriculuar
description:


service:
-
    description: Student Mentor for ACL 2020 Student Research Workshop
-
    description: Program Committee Member for ACL (2018, 2019, 2020)
-
    description: Program Committee Member for NAACL (2018, 2019)
-
    description: Program Committee Member for EMNLP (2018, 2019)
-
    description: Program Committee Member for AAAI (2017, 2018)
-
    description: Program Committee Member for EACL 2017
-
    description: Program Committee Member for MRQA Workshop (2018, 2019)
-
    description: Program Committee Member for AKBC 2019

---

### Teaching
- Guest Lectures for CIS 520 - Machine Learning
- Teaching Assistant for CIS 700 - Reasoning in Artificial Intelligence
- Teaching Assistant for CIS 530 - Computation Linguistics


### Academic Service
{% for item in page.service %}
- {{ item.description }}
{% endfor %}
