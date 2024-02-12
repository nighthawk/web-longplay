---
layout: page
title: F.A.Q.
redirect_from:
  - /ios/faq/
permalink: /faq/
---

{% for group in site.data.faq %}

## {{ group.group }}

{% for question in group.questions %}

### {{ question.question }}

{{ question.answer | markdownify }}

{% endfor %}

---
<br />

{% endfor %}

### I got another question!

You can reach out on [Mastodon](https://indieapps.space/@longplay) or [by mail](mailto:words@longplay.app).
