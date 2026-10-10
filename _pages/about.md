---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

I am a first-year Ph.D. candidate at the Hong Kong University of Science and Technology (HKUST), where I am part of the HKUST NLP Group, advised by Professor Junxian He. My research focuses on natural language processing and machine learning. My research interests include LLM Reasoning and Reinforcement Learning, Hallucination in Vision-Language Models (VLM), and LLM Truthfulness and Interpretability.

Education
======
* **Ph.D. in Computer Science** (2024 – Present), Hong Kong University of Science and Technology (HKUST), HKUST NLP Group, advised by Professor Junxian He
* **B.Eng.** (2020 – 2024), Shanghai Jiao Tong University (SJTU), graduated in June 2024, previously advised by Professor Junxian He
  * Honors: Zhiyuan Honor Scholarship

Research Experience
======
* **Research Intern at MINIMAX** (February 2025 – Present)
* **Research Intern at Tencent WXG** (June 2024 – September 2024)
  * Advisor: Zifei Shan
* **Research Intern at Shanghai AI Lab** (June 2023 – December 2023)
  * Advisor: Prof. Yu Cheng

Skills
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Publications
======
<ol class="bibliography">
{% for post in site.publications reversed %}
  <li><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a>, <i>{{ post.venue }}</i>, {{ post.date | default: "1900-01-01" | date: "%Y" }}<br />{{ post.citation }}</li>
{% endfor %}
</ol>

Contact
======
* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
