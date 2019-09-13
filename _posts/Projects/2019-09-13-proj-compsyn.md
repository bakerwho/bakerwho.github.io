---
layout: project
title: Computational Synesthesia
comments: true
categories: Project
tags:
  - color synesthesia cognition complex
hidden: false
---

I was fortunate to join a multidisciplinary, very intelligent, and very skilled cohort at the Santa Fe Institute's Complex Systems Summer School, 2019 (CSSS19).

Over discussions on the dependence of art of its observer, on an objective framework for judging art, and other meta-commentary, an idea was born to attempt to trace color as a root of meaning.

In our attempt to formalize the analysis, we dipped into color theory, cognitive theory, machine learning, and information theory.

The result was [compsyn](https://github.com/bakerwho/comp-syn) - a Python package that offers a novel method to explore relationships between words and abstract concepts through color.

The image below used our `get_composite_image()` method to generate what we call a colorgram of pictures of the entire CSSS19 cohort.

![CSSS19 composite image](/images/2019/csssfaces_composite.png)

We now have a quantitative framework with which we can analyze digital images in a perceptually uniform colorspace and measure the statistical relationships between color and cognition.

`pip install compsyn` to try it yourself.