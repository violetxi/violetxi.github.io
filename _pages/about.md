---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in Psychology at Stanford University and a member of the [Stanford Autonomous Agents Lab](https://www.autonomousagents.stanford.edu/). I work with [Nick Haber](https://profiles.stanford.edu/nicholas-haber) and [Aviral Kumar](https://aviralkumar2907.github.io/).

My research interests span **exploration and scientific discovery through reinforcement learning**, **test-time learning**, and **learning in open-ended domains** such as creative writing. I bring a computational cognitive science perspective to questions about how agents learn, reason, and explore.

<details class="background-details">
  <summary>Background</summary>
  <p>Previously, I earned an M.S. in Computer Science and undergraduate degrees in Informatics and Mathematics at Indiana University.</p>
</details>

[CV (PDF)]({{ '/files/CV_Violet.pdf' | relative_url }}) · [Google Scholar](https://scholar.google.com/citations?user=1LQU1CQAAAAJ&hl=en) · [GitHub](https://github.com/violetxi) · [Email](mailto:ziyxiang@stanford.edu)

## Selected research

{% assign selected_publications = site.publications | where: "selected", true | sort: "order" %}
{% for publication in selected_publications %}
  {% include publication-item.html publication=publication compact=true %}
{% endfor %}

[View all publications →]({{ '/publications/' | relative_url }})

## Industry research

{% include industry-experience.html %}
