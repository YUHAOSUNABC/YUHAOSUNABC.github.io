---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year PhD student in the School of Computing and Information Systems, Faculty of Engineering and Information Technology, at The University of Melbourne.

My research focuses on **agent safety** and **trustworthy machine learning** — building AI systems, and autonomous agents in particular, that behave reliably, safely, and as intended.

I am fortunate to be advised by A/Prof. Xingliang Yuan and Dr. Shaanan Cohney, and I also work closely with Dr. Feng Liu. Previously, during my master's degree, I conducted research in the TMLR Group, Melbourne, advised by Dr. Feng Liu.

I am always happy to discuss research and potential collaborations. Feel free to reach out at [yuhaos1@student.unimelb.edu.au](mailto:yuhaos1@student.unimelb.edu.au) or [asymptote1527@gmail.com](mailto:asymptote1527@gmail.com).

## Research interests

- Agent safety
- Trustworthy machine learning

## News

- *Stay tuned — updates coming soon.*

## Publications

You can also find my articles on [my Google Scholar profile]({{ site.author.googlescholar }}).

{% for category in site.publication_category %}
{% assign title_shown = false %}
{% for post in site.publications reversed %}
{% if post.category != category[0] %}{% continue %}{% endif %}
{% unless title_shown %}
<h3 class="publication-category">{{ category[1].title }}</h3>
{% assign title_shown = true %}
{% endunless %}
{% include archive-single.html %}
{% endfor %}
{% endfor %}

## Education

- **Ph.D. in Computer Science**, The University of Melbourne — School of Computing and Information Systems, Faculty of Engineering and Information Technology · Aug 2025 – present
- **M.S. in Information Technology (Artificial Intelligence)**, The University of Melbourne · Feb 2023 – Jun 2024 *(with Distinction)*
- **B.S. in Computer Science**, The University of Melbourne · Feb 2020 – Nov 2022

## Academic service

- Reviewer, *International Conference on Machine Learning (ICML)*, 2025, 2026
- Reviewer, *International Conference on Learning Representations (ICLR)*, 2026
- Reviewer, *Transactions on Machine Learning Research (TMLR)*
- Reviewer, *Neural Networks*
