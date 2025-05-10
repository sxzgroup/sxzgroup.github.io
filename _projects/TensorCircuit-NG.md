---
layout: page
title: TensorCircuit-NG
description: Tensor network based quantum software framework - next generation
img: assets/img/TCNG-black.jpg
importance: 1
category: work
related_publications: true
github_repos: ["refraction-ray/tensorcircuit", "tencent-quantum-lab/tensorcircuit", "tensorcircuit/tensorcircuit-ng"]
---

## Introduction

<p style="text-align: justify;">
TensorCircuit-NG is a high-performance, open-source quantum software framework designed to power the next generation of quantum computing research and development. Engineered to overcome limitations in existing platforms, TensorCircuit-NG features a sophisticated tensor network engine that delivers unparalleled simulation speed and scalability. Built with seamless integration with leading machine learning frameworks like TensorFlow, JAX, and PyTorch, it provides a versatile and efficient environment for exploring both quantum algorithms and hybrid quantum-classical approaches.
</p>

<p style="text-align: justify;">
At its core, TensorCircuit-NG offers significant performance advantages, achieving speedups of up to 10^6 compared to other major software on common tasks and enabling the simulation of 100-1000 qubits for specific structures. Its deep integration with the ML ecosystem facilitates advanced features like automatic differentiation, GPU/TPU acceleration, and the flexible composition of quantum circuits, tensor networks, and neural networks. TensorCircuit-NG's universality covers a wide range of simulation scenarios, from exact and noisy circuit simulation to more specialized areas like fermionic or qudit systems.
</p>

<p style="text-align: justify;">
TensorCircuit-NG has rapidly become a foundational tool for quantum computing worldwide. With over 800,000 downloads and cited in more than 100 research publications, its user base spans prestigious global institutions including Harvard, MIT, Caltech, Tsinghua, and Peking University, alongside industry leaders like NVIDIA, IBM, and Google. Its adoption by top labs underscores its recognized excellence. TensorCircuit-NG's impact is further highlighted by its selection as a top10 quantum industry event in QuantumChina and its unique inclusion in NVIDIA cuQuantum performance benchmarks.
</p>

## Links

- <a href="https://github.com/tensorcircuit/tensorcircuit-ng" target="_blank"><i class="fab fa-github"></i> Repo</a>: https://github.com/tensorcircuit/tensorcircuit-ng

- <a href="https://tensorcircuit-ng.readthedocs.io/" target="_blank"><i class="fas fa-book"></i> Documentation</a>: https://tensorcircuit-ng.readthedocs.io/

- <a href="https://pypi.org/project/tensorcircuit-ng/" target="_blank"><i class="fab fa-python"></i> PyPI</a>: https://pypi.org/project/tensorcircuit-ng/

## The whitepaper

- The whitepaper for TensorCircuit of v0.x: {% cite Zhang2022_tc %}

## History of the package

See [here](https://github.com/tensorcircuit/tensorcircuit-ng/blob/master/HISTORY.md) for the brief history of TensorCircuit.

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in page.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
