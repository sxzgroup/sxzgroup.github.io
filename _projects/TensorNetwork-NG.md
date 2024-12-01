---
layout: page
title: TensorNetwork-NG
description: Tensor network toolbox with backend agnosticism - next generation
img: assets/img/tn_logo.png
importance: 2
category: work
related_publications: false
github_repos: ["google/TensorNetwork", "refraction-ray/TensorNetwork-NG"]
---

TensorNetwork-NG is an open-source tensor network software compatible within machine learning infrastructure.

## Links

- <a href="https://github.com/refraction-ray/TensorNetwork-NG" target="_blank"><i class="fab fa-github"></i> Repo</a>: https://github.com/refraction-ray/TensorNetwork-NG

- <a href="https://pypi.org/project/tensornetwork-ng/" target="_blank"><i class="fab fa-python"></i> PyPI</a>: https://pypi.org/project/tensornetwork-ng/

## History of the package

This package was originally developed by the Google team. Recognizing that the original package is no longer under active maintenance, I have forked the NG branch to ensure its ongoing compatibility with the rapidly evolving scientific computing ecosystem and infrastructure.

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in page.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
