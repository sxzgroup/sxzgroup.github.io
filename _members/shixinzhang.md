---
layout: about
inline: false
group: Faculty
group_rank: 1

title: Prof. Shi-Xin Zhang
page_title: true
description:
lastname: Zhang

teaser: >
  I’m an Associate Professor at Institue of Physics, Chinese Academy of Sciences.
  Previously, I was a Senior Research Scientist at Tencent Quantum Lab.
  <br />
  <br />

profile:
  name: Shi-Xin Zhang (张士欣)
  position: >
    Principal Investigator<br />
    Associate Professor<br />
    Institue of Physics<br />
    Chinese Academy of Sciences<br />
  align: middle
  image: 001landscape.jpg
  miniimage: 001.png
  email: shixinzhang@iphy.ac.cn
  linkedin: zhangshixin
  orcid: 0000-0003-0347-9750
  scholar: Ut8nVqIAAAAJ
  github: refraction-ray
  website: https://re-ra.xyz
  edu: https://iop.cas.cn/rcjy/tpyjy/?id=6789
  address: >
    Beijing, China
---

<br>

See my academic CV [here](https://re-ra.xyz/about/cv.pdf).

## Experience

- 2024.8 - now, Institute of Physics, Chinese Academy of Sciences, Associate Professor

- 2021.7 - 2024.7, Tencent Quantum Laboratory, Senior Research Scientist

## Education

- 2016.8 - 2021.7, Institue for Advanced Study, Tsinghua University, PhD in Physics

- 2012.8 - 2016.7, Department of Physics, Tsinghua University, BSc in Physics

## Achievements

#### Quantum Software

Created and developed TensorCircuit:

- An open-source, high-performance quantum software that provides a unified interface and infrastructure for quantum programming.

- Built upon modern machine learning frameworks including TensorFlow, Jax, and PyTorch, and features an advanced tensor network contraction engine. This enables the seamless integration of tensor networks, neural networks, and quantum circuits.

- Offers comprehensive solutions for hybrid CPU-GPU-QPU and distributed computing.

- Widely adopted by universities, research institutes, and companies worldwide, with over 100 citations, including from research teams at Google, NVIDIA, IBM, and leading academic groups at Harvard, Caltech, and Chicago.

- Selected as one of the "Top 10 Influential Events in 2022" by QuantumChina.

- The only quantum software as the official baseline for NVIDIA's cuQuantum in its release.

#### Quantum Algorithms

- Pioneered the concept and terminology of Quantum Architecture Search (QAS). This work catalyzed the emergence of the field and established new paradigms for automated quantum circuit design. A search for "Quantum Architecture Search" on Google Scholar yields over 400 academic papers.

- Developed a hybrid wavefunction ansatz that efficiently fuses quantum circuits with neural networks. This approach significantly boosts the model's expressive power and achieves an exponential speedup over non-unitary methods proposed by IBM's team.

#### Non-Equilibrium Quantum Physics

- Developed the theory of the quasiperiodic many-body localized (MBL) phase and phase transitions. Performed the first large-scale simulation to determine the universality class of the critical behavior in quasiperiodic MBL, establishing its robustness against random disorder.

- Conducted the first investigation of the Quantum Mpemba Effect in both thermalized and MBL systems, proposing a general physical mechanism for its occurrence in generic quantum many-body systems. Pioneered the study of the Mpemba effect in the context of SU(2) symmetry, symmetry-breaking dynamics, and imaginary-time evolution, significantly impacting the field and substantially broadening the scope of Mpemba effect.

- Systematically investigated the interplay between random unitary evolution, measurement, and noise, with the work being cited by Google's experimental paper in Nature.

#### Differentiable Programming

- Extended the paradigm of differentiable programming to a broader range of operators and workflows in quantum physics. Theoretically derived the gradients for the complex-valued singular value decomposition and contributed the implementation to TensorFlow.

- My Ph.D. thesis, "Differentiable Programming in Quantum Physics," was awarded the Tsinghua University Excellent Doctoral Dissertation Award.

## Open Source

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo_user.liquid username="refraction-ray" %}
</div>

  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username="refraction-ray" %}
  </div>
---

## Patents

Applied for over 40 domestic and international patents focusing on key technologies in quantum computing.

---

## Publications

<div class="publications">
{% bibliography -f papers -q @*[author^=*Shi-Xin]* %}
</div>
