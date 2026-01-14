---
layout: page
title: 제조를 위한 인공지능
description: >-
    Course policies and information.
---

# 제조를 위한 인공지능
Artificial Intelligence for Manufacturing

M2866.004300
> As our understanding deepens of how humans interact with the physical world through perception, judgment, and action to create structure and function, artificial intelligence is expanding beyond simple prediction and automation toward Physical AI, systems that make decisions, take actions, and produce physical outcomes. This shift is expected to bring a fundamental transformation to manufacturing, a domain that has traditionally remained outside the full scope of automation. This course reinterprets manufacturing not as a problem of process optimization or data-driven prediction, but as an intelligent system that actively creates in the physical world, inspired by principles derived from living systems. The course examines biological manufacturing processes from the level of single cells to neural learning and plasticity, and explores the foundations of visual, language, and generative intelligence to understand their implications for manufacturing system design. Going beyond conventional manufacturing AI applications such as inspection, prediction, and maintenance, students address real-world challenges across the manufacturing lifecycle, including product and structural design, intelligent manufacturing systems, and human–AI–machine collaboration. Through projects based on their own company domains and data, students design and evaluate manufacturing AI systems with an emphasis on explainability, responsibility, and safety, developing practical capabilities for applying Physical AI in real industrial environments.

- __Location__: Bld 38-429
- __Lecture__: Wednesday 14:00 – 16:50
  

## Teaching Assistant
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_ai_for_manufacturing' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

---

## Grading
- Attendance: 5%
- Assignment: 40%
- Final Exam: 25%
- Attitude: 5%
- Project: 25%

## Assignment
- Defective PCB Detection
  - [Reference Paper](https://www.nature.com/articles/s41597-024-03656-8)    
  - [Dataset](https://figshare.com/articles/dataset/DsPCBSD_/24970329?file=44069552)
- Classification of Vibration Signal
  - [Reference Paper](https://ieeexplore.ieee.org/document/9078761)
  - [Dataset](https://engineering.case.edu/bearingdatacenter/download-data-file)
- LLM with Digital Twin
  - [Reference Paper](https://ieeexplore.ieee.org/document/10710900)


| Phase | Week | Date | Topic | Lab session / Activity |
|:----|:----:|:----:|----|------|
| **Phase I – Manufacturing from Living Systems** | 1 | 3/4 | Course Introduction: Why **Physical AI** for Manufacturing<br />- Overview of course structure and projects | - |

## References
- Mingu Jeon, In-Ho Choi, Seung-Woo Seo, and Seong-Woo Kim, "Extremely Rare Anomaly Detection Pipeline in Semiconductor Bonding Process with Digital Twin-driven Data Augmentation Method," IEEE Transactions on Components, Packaging and Manufacturing Technology, Vol. 14, No. 10, pp. 1891 - 1902, Oct. 2024
- Gyuho Lee, Seong-Woo Kim, and Mingu Jeon, “Machinery Value Estimation Method based on IIoT System Utilizing 1D-CNN Model for Low Sampling Rate Vibration Signals from MEMS,” IEEE Internet of Things Journal, Vol. 10, No. 14, pp. 12261-12275, July. 2023
- Mingu Jeon, Siyun Yoo, and Seong-Woo Kim, "A Contactless PCBA Defect Detection Method: Convolutional Neural Networks with Thermographic Images," IEEE Transactions on Components, Packaging and Manufacturing Technology, Vol. 12, No. 3, pp 489 - 501, March 2022
