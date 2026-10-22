---
layout: page
title: Free Energy to LLMs
description: Generative models and probability, from variational free energy to LLM training and inference (in Chinese)
img: assets/img/free_energy_to_llms.png
importance: 1
github_repos: ["refraction-ray/free-energy-to-llms"]
---

## Introduction

<p style="text-align: justify;">
An open textbook on generative models, written from the viewpoint of statistical physics and probability and carried from mathematical derivation all the way to engineering practice. For every model it asks four questions: which distribution it represents, which objective it learns with, how it samples, and where the real bottleneck lies.
</p>

<p style="text-align: justify;">
The book covers VAE, normalizing flows, GAN, diffusion and energy-based models, then Transformer, multimodal models and reinforcement-learning post-training, followed by training systems, inference systems, agent systems and the architecture innovations of DeepSeek and Kimi, and finally returns to generative models in scientific computing. It has about 150 pages in 11 chapters and 2 appendices, with 34 TikZ figures whose sources are released together with the book.
</p>

## Courses

- Oct 2026, Graduate School of China Academy of Engineering Physics: three 50-minute lectures. Slides are in the [`slides/`](https://github.com/refraction-ray/free-energy-to-llms/tree/main/slides) folder of the repo.

## Links

- <a href="https://github.com/refraction-ray/free-energy-to-llms" target="_blank"><i class="fab fa-github"></i> Repo</a>: https://github.com/refraction-ray/free-energy-to-llms

- <a href="https://github.com/refraction-ray/free-energy-to-llms/releases/latest" target="_blank"><i class="fas fa-file-pdf"></i> PDF</a>: https://github.com/refraction-ray/free-energy-to-llms/releases/latest

The text, figures, slides and their sources are released under CC BY-NC-SA 4.0.

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in page.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
