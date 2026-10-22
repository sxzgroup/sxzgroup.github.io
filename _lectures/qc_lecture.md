---
layout: page
title: Quantum Computing Basics
description: Introduction to quantum computing with code demos in TensorCircuit-NG
img: assets/img/qc_lecture_logo.png
importance: 2
github_repos: ["sxzgroup/qc_lecture"]
---

## Introduction

<p style="text-align: justify;">
Lecture materials for an introduction to quantum computing, prepared for the <a href="https://indico.ihep.ac.cn/event/24170/" target="_blank">1st Machine Learning and Quantum Computing Winter School</a> at Nankai University (Jan 2025). The slides introduce the basics of quantum computing, and four Jupyter notebooks walk through the same material with runnable code in <a href="https://github.com/tensorcircuit/tensorcircuit-ng" target="_blank">TensorCircuit-NG</a>:
</p>

- Ingredients of quantum computing
- Quantum algorithms
- Quantum computing in the NISQ era
- Quantum errors

The notebooks also serve as a hands-on introduction to the representative usage of TensorCircuit-NG.

## Links

- <a href="https://github.com/sxzgroup/qc_lecture" target="_blank"><i class="fab fa-github"></i> Repo</a>: https://github.com/sxzgroup/qc_lecture

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in page.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
