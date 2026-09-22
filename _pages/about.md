---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in Psychology at **Stanford University**, working in the [Stanford Autonomous Agents Lab](https://www.autonomousagents.stanford.edu/) with [Nick Haber](https://profiles.stanford.edu/nicholas-haber). My research focuses on **LLM post-training, reinforcement learning, and reward modeling**, with roots in computational cognitive science.

I study how to train language models to reason more effectively, how to provide useful feedback during learning, and how to evaluate what models learn. My recent work spans dense rewards for exploratory RL, adaptive reasoning budgets, reward-model biases, and human-preference evaluation. I also work on theory of mind in multi-agent systems and benchmarks connecting human and machine learning.

Previously, I earned an M.S. in Computer Science and undergraduate degrees in Informatics and Mathematics at Indiana University.

[CV (PDF)]({{ '/files/CV_Violet.pdf' | relative_url }}) · [Google Scholar](https://scholar.google.com/citations?user=1LQU1CQAAAAJ&hl=en) · [GitHub](https://github.com/violetxi) · [Email](mailto:ziyxiang@stanford.edu)

## Selected research

{% assign selected_publications = site.publications | where: "selected", true | sort: "order" %}
{% for publication in selected_publications %}
  {% include publication-item.html publication=publication compact=true %}
{% endfor %}

[View all publications →]({{ '/publications/' | relative_url }})

## Industry research

{% include industry-experience.html %}
