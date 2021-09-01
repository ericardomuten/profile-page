---
title: Quantum Convolutional Neural Networks for High-Energy Physics Analysis at
  the LHC
date: 2021-09-01
summary: A Google Summer of Code 2021 Project Repository. This project aims to
  demonstrate quantum machine learning's potential, specifically Quantum
  Convolutional Neural Network (QCNN), in HEP events classification from
  particle image data. The code used in the research is wrapped as an
  open-source package to ease future research in this field.
draft: false
featured: true
tags:
  - Quantum Machine Learning
  - High-Energy Physics
external_link: 
links:
  - url: https://summerofcode.withgoogle.com/projects/#5612096894533632
    name: Go to Project Site
    icon_pack: 
    icon: 
  - url: https://github.com/eraraya-ricardo/qcnn-hep
    name: GitHub
    icon_pack: fab
    icon: github
  - name: v1.0.0
    icon_pack: fas
    icon: code-branch
  - url: https://opensource.org/licenses/MIT
    name: MIT License
    icon_pack: fas
    icon: copyright
  - name: Open Source
    icon_pack: fas
    icon: heart
  
# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
# alt_text: An optional description of the image for screen readers.
image:
  placement: 1
  caption: ""
  focal_point: "Center"
  preview_only: false
#  alt_text: An optional description of the image for screen readers.
---

<div align="center">

<a href="https://gist.github.com/eraraya-ricardo/8391f6bdae596e82fe0260c215c5ab8c" target="_blank"><img src="https://img.shields.io/badge/Google%20Summer%20of%20Code-2021-fbbc05?style=flat&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAGQAAABkCAMAAABHPGVmAAAALVBMVEVHcEz7vQD7vQD8vQD7vQD8vQD7vQD8vQD8vQD7vQD7vQD8vQD7vQD7vQD7vQAgxtLpAAAADnRSTlMAZvVQ6QrVPhl6oSmHvzL6LQUAAASGSURBVHjatdnZdusgDAVQELMY%2Fv9zb2%2Bwc%2BIKDzQLvTXB3gYBFqmaDVeKU4sCBlFyy43WqLjlBpR1BpR1BpR1xjoFxmIFBpSVBpSVBpSVBpSVBpQ1xvdK1oPgblhfOWltjNaJq7ddYT2IfImYJqMDrENUChGDZn%2FWQ%2FMHxBcD4BMyBc5XCHkNQTq60vfIgXAx5xByju6T8V8itsT3%2FUPi6r39Ce8rp%2FCWYrHfIDXs95FZJs%2FvTob6Z4T2buQE4eikvHeG%2FoZY7TpRfDsNWzrjtP0L4s12NYhh%2BO1ZjJ9HfOjdYGo3QZx7YvwEAgOPdx3eQJlArMFA3wXSZ%2BwMQvplJGoPY6sqNU0gxcGYUVx5jtSIx3oS6HysTxEbMMDPAmkM9iFSXnPXt8nwuQ%2FYI8TH%2F425TQe7%2FnBPEH2bECI6T4t%2Bgvh4N1istR50FJdeIX1Ek%2FqJdGGQOWmAa4u7rn18vuuIzUq52gbxvpiSuzIau%2BuO9FUUfTvvCjcoQ4MMltRnEOqF0pdD%2FwiBZWxoqGCn8r2VGKIUCHOoTyHK2g7y1bsJRRqNe3%2FlXv5GbNhWEWXxbsf1UITRF4kYcM4KiI%2FbeFIevNNq7P2EIg0bVL%2BfqCcyYV2rbDdExWSPjUPPGBRh9JTowTscW0Dqf%2BwLXGmPthgKKMJo1f1OSQ29hf1Mbdlmg5NFV1H7KoICA3mruIQ4vl4TTFhvuAlxxrdb1J55KMJoBatEPCv6mr3sJzK%2F9RQKDAx49Ji5ctSLwsxAxgyuiduOAeVtIG14zppPKtAka9lcMZz71IHyNoAcCpvIx6UfxGLleCim3ggUpe0dQhe7I86mWvQERZmCIocryAqPsdYOSQlVIjCgyMRbLSaXxi3GD4LEw4AipzCyyvS5a5ThMpJTGAYUuQljhiWL53R11FN5BxhQsK0UWbE747E7evGV2FaEAUWmDave0H4LQxg6nErl1IEBBRdmOzjkBPpdqFB%2BpUtUGb0tDKloZP44hQLthQoDwXYiXlowpMJIymExdARL8SViYzymhGEMFR%2FR3cOyNoRCpQcZFu1s6AsNhlQuSiJP%2B1Kk90dNRHW9BYyhwlszhNgdb05CjmGcKDb3DotAoYIYV9wWxjDSZcHNmN%2Fj0KpPm3R7dMjq7HlrSokvjIqjww3SEhb4XJDpg3CLvM9%2BPG%2FMHOcaOwzYRFScNe8QHJb9nOEDhvkGwV48eZC3BgfzWwSHZaXthKEVMvkMaQnKhKESzSCkJ37uQqlJ7RmCIcbr%2By5qUEjiIwQK3q4yZKHqYDxEUIo4U6%2BNahxKr0kEZwv8HC%2BDqo69UaI2ieBAujN2RNhOoPybQjBr9oNSKNXSoQ%2B2luCUQuk1iSCIg9oiZl24Vv8TtXLROaotAtO3%2F9ooWSFcjDnH6BQio2SZQSRz%2FpsPfsifQ2RY1tmNBM3oxQRCbRjkOZn%2FEACT2J%2B1vkZiGESyG1SZS%2FqJ1wTogE1hEFHNh9yNCbvvREwqCwwoawwoKw0oKw0oKw0oKw0oKw0oKw0oMFYqMFYqMFYqMBYq88Y%2FxB7wiOJRvWkAAAAASUVORK5CYII%3D" /></a>

A Google Summer of Code 2021 Project Repository

</div>

- **Organization**
  - [Machine Learning for Science (ML4Sci)](https://ml4sci.org/)
- **Student**
  - [Eraraya Ricardo Muten](https://eraraya-ricardo.me/)
- **Mentors**
  - [Prof. Sergei V. Gleyzer](http://sergeigleyzer.com/), [Dr. Emanuele Usai](https://orcid.org/0000-0001-9323-2107), and [Raphael Koh](https://www.raphaelkoh.me/)
- **Project Details**
  - [Project Idea](https://ml4sci.org/gsoc/2021/proposal_QMLHEP2.html)
  - [Accepted Proposal](https://raw.githubusercontent.com/eraraya-ricardo/qml-hep-gsoc-2021/main/Eraraya_Ricardo_Muten_GSoC_2021_Proposal_QCNN.pdf)

## Introduction

One of the challenges in High-Energy Physics (HEP) is events classification, which is to predict whether an image of particle jets belongs to events being sought after or just background signals. Classical Convolutional Neural Network (CNN) has been proven a powerful algorithm in image classification, including jets image. As quantum computers promise many advantages over classical computing, comes a question on whether quantum machine learning (QML) can give any improvement in solving the problem. This project aims to demonstrate quantum machine learning's potential, specifically Quantum Convolutional Neural Network (QCNN), in HEP events classification from image data. The code used in the research is wrapped as an open-source package to ease future research in this field.

## How to Use

### Package Description
This package is a [TensorFlow Quantum](https://www.tensorflow.org/quantum) implementation of quantum convolution and classifier with [Data Re-uploading](https://quantum-journal.org/papers/q-2020-02-06-226/) ansatz. Both are wrapped as [Keras](https://keras.io/) layers that can easily be integrated into other Keras layers (classical and/or quantum), acting as building blocks for Quantum Convolutional Neural Networks (both hybrid and fully quantum). The model can be trained using Keras API.

### Installation
```shell
git clone https://github.com/eraraya-ricardo/qcnn-hep.git
cd qcnn-hep
python -m pip install -r requirements.txt
python setup.py
```
For a more detail step-by-step installation, please refer to [Docs and Tutorial](https://github.com/eraraya-ricardo/qcnn-hep#docs-and-tutorial).
