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

<div class="news-scroll" markdown="0">
<ul>
<li><span class="news-date">Jun 2026</span> Released our preprint <a href="https://yuhaosunabc.github.io/TRIAD/"><b>TRIAD</b></a> — <em>From Risk Classification to Action Plan Remediation: A Guardrail Feedback Driven Framework for LLM Agents</em>.</li>
<li><span class="news-date">Feb 2026</span> <a href="https://arxiv.org/abs/2601.20419"><b>BiFTA</b></a> was accepted to <b>TMLR</b>! 🎉</li>
<li><span class="news-date">Jan 2026</span> Our paper on stealthy fine-tuning data extraction was accepted to <b>ICLR 2026</b>! 🎉</li>
<li><span class="news-date">May 2025</span> <a href="https://arxiv.org/abs/2506.06027"><b>SSNI</b></a> was accepted to <b>ICML 2025</b>! 🎉</li>
</ul>
</div>

## Publications

You can also find my articles on [my Google Scholar profile]({{ site.author.googlescholar }}).

<div class="pub-list">
{% assign pubs = site.publications | sort: 'date' %}
{% for post in pubs reversed %}
{% include publication-card.html %}
{% endfor %}
</div>

## Education

- **Ph.D. in Computer Science**, The University of Melbourne — School of Computing and Information Systems, Faculty of Engineering and Information Technology · Aug 2025 – present
- **M.S. in Information Technology (Artificial Intelligence)**, The University of Melbourne · Feb 2023 – Jun 2024 *(with Distinction)*
- **B.S. in Computer Science**, The University of Melbourne · Feb 2020 – Nov 2022

## Academic service

- Reviewer, *ICML*, 2025, 2026
- Reviewer, *ICLR*, 2026
- Reviewer, *TMLR*
- Reviewer, *Neural Networks*
