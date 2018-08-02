---
type: navigation
---

# Tracking Progress in Natural Language Processing

### Table of contents

{% for page in site.pages %} {% if page.type != "navigation" and page.title %}
* [{{ page.title }}]({{ site.url }}{{ page.url }}) {% endif %} {% endfor %}

### Description

This document aims to track the progress in Natural Language Processing (NLP) and give an overview
of the state-of-the-art (SOTA) across the most common NLP tasks and their corresponding datasets.

It aims to cover both traditional and core NLP tasks such as dependency parsing and part-of-speech tagging
as well as more recent ones such as reading comprehension and natural language inference. The main objective
is to provide the reader with a quick overview of benchmark datasets and the state-of-the-art for their
task of interest, which serves as a stepping stone for further research. To this end, if there is a
place where results for a task are already published and regularly maintained, such as a public leaderboard,
the reader will be pointed there.

If you want to find this document again in the future, just go to [`nlpprogress.com`](https://nlpprogress.com/)
or [`nlpsota.com`](http://nlpsota.com/) in your browser.

### Contributing

Visit GitHub repository [sebastianruder/NLP-progress](https://github.com/sebastianruder/NLP-progress).
