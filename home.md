---
layout: home
title: 2026 Spring Courseworks
nav_exclude: true
permalink: /:path/
---

# 2026 Spring Courseworks
Courseworks in 2026 spring, Autonomous Robot Intelligence Lab
- [머신러닝을 위한 기초 수학 및 프로그래밍 실습](./basic_machine_learning.md)(Basic Mathematics and Programming Practice for Machine Learning, M2177.005800)
- [제조를 위한 인공지능](./ai_for_manufacturing.md)(Artificial Intelligence for Manufacturing, M2866.004300)
- [태양광 자동차](./solar_car.md)(Solar Car Capstone Design, M2177.011500)
  
## Instructor
{% assign instructors = site.staffers | where: 'role', 'instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
