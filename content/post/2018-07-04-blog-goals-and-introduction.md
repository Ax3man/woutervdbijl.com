---
title: Blog goals and introduction
author: ~
date: '2018-07-04'
slug: blog-goals-and-introduction
categories: []
tags: []
header:
  caption: ''
  image: ''
---

I'm starting an irregular blog. The goals and use of the blog will probably develop with time, but for now I'm envisioning it as a blog on reproducibility in research. Specifically, I want to take papers that I found interesting and that are relatively recent, and see how far I can get in reproducing the figures and analyses from the paper, supplementary material and the publicly posted data.

Some of the motivation for this comes from the experience of looking at some published work and getting frustrated being unable to reproduce even basic results, while other work may be absolutely trivial to reproduce. Unfortunately, the incentives in publishing are not really encouraging authors to make it easy for others. Creating easily reproducible and well-documented data and analyses takes time and often will help little in getting your paper accepted (at least in my experience). I find that I struggle with this too, and want to improve in this regard.

Secondly, there are sometimes many ways to analyze a dataset, and I'm curious how much the chosen strategy affects the outcome of the study.

By recreating some analysis I hope to make it insightful to myself and to my readers what is required to make your data useful and your analysis reproducible, and find common pitfalls to avoid. It will also make it apparent where I would make a different analysis plan than others.

All blog entries will be rendered R markdown, and include all code to reproduce my work.

The general strategy will be as follows:

- I read the intro and general methods of the paper, but skip the stats section entirely.
- I get the data and try to answer the (most impotant) questions of the researchers independently.
- I recreate the (most important) figures from the paper, and propose alternative visualizations if it might be useful.
- I see whether my analysis reproduces the result of the authors.
- If not, I try to reproduce the same analysis the authors did and discuss the differences.
- I reflect on the analysis, and the difficulties in recreating the result.


