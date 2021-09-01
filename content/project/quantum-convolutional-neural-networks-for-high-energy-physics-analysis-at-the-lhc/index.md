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
external_link: https://summerofcode.withgoogle.com/projects/#5612096894533632
links:
  - url: https://github.com/eraraya-ricardo/qcnn-hep
    name: GitHub
    icon_pack: fab
    icon: github
  
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
  
![version](https://img.shields.io/badge/version-1.0.0-blue)[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v2/open-source.svg)](https://github.com/firstcontributions/open-source-badges)

A Google Summer of Code 2021 Project Repository

</div>


## Introduction

- **Organization**
  - [Machine Learning for Science (ML4Sci)](https://ml4sci.org/)
- **Student**
  - [Eraraya Ricardo Muten](https://eraraya-ricardo.me/)
- **Mentors**
  - [Prof. Sergei V. Gleyzer](http://sergeigleyzer.com/), [Dr. Emanuele Usai](https://orcid.org/0000-0001-9323-2107), and [Raphael Koh](https://www.raphaelkoh.me/)
- **Project Details**
  - [Project Idea](https://ml4sci.org/gsoc/2021/proposal_QMLHEP2.html)
  - [Accepted Proposal](https://raw.githubusercontent.com/eraraya-ricardo/qml-hep-gsoc-2021/main/Eraraya_Ricardo_Muten_GSoC_2021_Proposal_QCNN.pdf)
  - [Official Project Page](https://summerofcode.withgoogle.com/projects/#5612096894533632)

### Abstract

One of the challenges in High-Energy Physics (HEP) is events classification, which is to predict whether an image of particle jets belongs to events being sought after or just background signals. Classical Convolutional Neural Network (CNN) has been proven a powerful algorithm in image classification, including jets image. As quantum computers promise many advantages over classical computing, comes a question on whether quantum machine learning (QML) can give any improvement in solving the problem. This project aims to demonstrate quantum machine learning's potential, specifically Quantum Convolutional Neural Network (QCNN), in HEP events classification from image data. The code used in the research is wrapped as an open-source package to ease future research in this field.

## How to Use

### Package Description
This package is a [TensorFlow Quantum](https://www.tensorflow.org/quantum) implementation of quantum convolution and classifier with Data Re-uploading[[3](#references)] ansatz. Both are wrapped as [Keras](https://keras.io/) layers that can easily be integrated into other Keras layers (classical and/or quantum), acting as building blocks for Quantum Convolutional Neural Networks (both hybrid and fully quantum). The model can be trained using Keras API.

### Package Dependencies
{{<href="https://www.python.org/" target="_blank"><img alt="Python" height="23px" src="https://img.shields.io/badge/Python%203.7-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white" /></>}}{{<href="https://quantumai.google/cirq" target="_blank"><img alt="Cirq" height="23px" src="https://img.shields.io/badge/Cirq%200.11.0-%23fff2c8.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAMAAAADACAMAAABlApw1AAAACVBMVEUAAAD%2F%2F%2F8AAABzxoNxAAAAAnRSTlMAAHaTzTgAAAMbSURBVHja7d2BZjRJFIbhb8%2F9X%2FSywjL8f3V5TndNxykITOJ9ur4QMZL88%2FIzgN8IGMAABjCAAcRO%2FXxYnGycJwH%2Fx5UTAAD5QDgO%2BGxzAgEg3y%2FBAZjvBAdovxMcYPkucIDlOwEA0A%2BEA4Banw1nP0Dy%2FRIAAP1AeBhQOydAcADl%2ByU4wPuJ4ADK9x05gPL9Ehzg%2FURwAOQDAQCQn6RJUASA%2Fj4CASA%2FSTURegFXn37zXTlgfxa9O3LAfk1aCQ7I7h56dwQAeZJ%2BCQ6whiABALAeJjiAHr%2FvyAGU7wQH%2BHp8Rw7o%2F4GmNqAGaM%2FfIzigeT37BAXc8%2FizQ0ZAf%2F72JRCgcz1O6AdQ%2Fg7eAL4eJzDA16M7QoCvxwkG8PX4jhDg6%2FFLQICvxwkKgHwnIMDX4wQGQL4LHID5TggAeD1OSAiA%2BU4IATDfBQkAdD1OSAiA%2BU4IATDfBYkA8t%2BBfCUkBMDH74QYQPP9OOBovgPqaL8DPP%2BbATlx%2Bn8r8VbAT%2F73Axb53w9Y5L8AsOj%2FesAi%2F%2FsBi%2FwXABb97wNUvRtQAxjAAAYwgAEMYAADGMAABjCAAQxgAAMYwAAGMIABDGAAAxjAAAYwgAEM4PcC6t2AqqonAOff%2FO2As2%2B%2Fd0A7oT7OI4Dqzf84TwCq7uuvegDQQ6g%2FngcALqi%2FngcARqg6CXBCnQesCZR%2FH8AFdam%2FbgI44Vp%2BPQmoas5PPQ2o6s0%2FAKi%2B8dcZQFXX%2BI8BquLrOQuo0vXcDViH0HoEkCwB1wQF6zFAloDKNQKshwDJCnCVAPkGSD4BsCNYDwDyCbAdbb%2FIAckHwAj7r3BA8gmgHe1%2FEQdkCXDCQvfA39yNEdaf3Qhwwma%2BA6BtDV3KHbAQwI422A7oJuzkVxxwx452vA7ov4SNVwLACH5XlW5AZ9vFfAL4JcBJBHCeEAGcJyQGcEGJIHHAwUtIGHCUkF6AEyzfAS4I5APgBCF3AZwg%2BQ545BKSU4AeQk4CnJAcBti3QnIQ4JeQnAQ4IecBsqPkIMAvITkPkP86mHMAJyzyCfCeM4ABDGAAAxjAq8%2B%2F636IWYQLuCcAAAAASUVORK5CYII%3D&logoColor=black" /></>}}
<span href="https://www.tensorflow.org/" target="_blank"><img alt="TensorFlow" height="23px" src="https://img.shields.io/badge/TensorFlow%202.4.1-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" /></span>
<a href="https://www.tensorflow.org/quantum" target="_blank"><img alt="TensorFlow Quantum" height="23px" src="https://img.shields.io/badge/TensorFlow--Quantum%200.5.1-%23425066.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAKgAAADNCAMAAAAbrMtvAAABMlBMVEUcR3oiSHcjSHcjSXckSXYlSXYmSHUnSXUoSXQrSXIrSnIuSnEwS3AxTG8yTG4yTG8zTG40TG40TW00TW41TW02TWw2TW03TWw5Tms8Tmk9Tmk%2FT2dAT2dAUGdBT2dBUGZBUGdCUGZDUGVDUGZDUWZEUGVFUWRFUWVGUWRKUmFKUmJMU2BTVF1WVFtYVVpbVlhbV1hiWlVsWk9tWk9vW05xW010XEt0XUt1XUt9YEaBYkSNYz2NZj2dZzWeZzShZzOhaDO7cyXCcCHDcSDDciDQcxrRdRnYdhXaeBTdehLiexDkew%2Flfg7oewzqewz6fgP6gAP%2BgwD%2FfgD%2FfwD%2FgAD%2FgQD%2FggD%2FgwD%2FhAD%2FhQD%2FhgD%2FhwD%2FiAD%2FiQD%2FigD%2F%2F%2F%2F5%2Bvr3%2Bfn09fb19vf29%2Fj%2F%2F%2F8Eoe3YAAAAZXRSTlMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADBQgI%2FPpD%2F74AAAR6SURBVHjaYoinFkhNjY%2BNi4sDUgBm56MAgSAIAJja%2BLfAjw63bUoUJERAVOsoj6i%2BUV6i9IzyEaVh1NcozaL8itIoyr%2BoLlEuonSIMhClPGowSmmU8ai6KFNRiqKmoxREWYmSHGU1KjPKRpS0qM0oKVH2o4RHORMVG%2BVYlLgoR6MERR2PEhAlIup0lKAoR6MCoxyLEht1Jkp4lP0oKVE2o9KibETJjLIYJTtqJUpBlNkoRVGmogqjDEepjRqLUh7lOkqLKBdRbaL8idIp6leUZlG%2BRWkY5SOqaZQbe%2FaO6zYMhGF0qSfN7H8Laa8Rxh758jXAfK2InwcqpaLQ6Dfa0IY2tKENbWhDi0H5PdR6KGIClLVQpkFZCDUVyiIos6FWQFkAZTrUIihToayDmgdlKZQ5UJZDmQC1BUoSmltcCfUbKBuhfAtlM5SvoA5AeQzlDNQzKMeg5KHMhD6XSkKthiakCShboHnqGMo2aJI6htoKTVDHUDZCM1JDKLuhCeq%2FUI5AE9RXqEPQBPUmaJSBRpSBRpSBRhlorIA2tKENbWhDG9rQhja0oQ1taEMbShkoZaDKQCkDpQxUGShloJSBUgaqDJQyUCKKQHkObWhDG9rQhka8dic0xl0GjXfdA41P3QGNTKeh%2BcpAI8pA4zooEtLj0LfD90A%2FTd8C%2FTx%2BBTQ1fwGUnPQw1LjboE%2FuOAh9eMkx6McvOldAx6j3Fx2AjkQJ6k5oQvPaQeiYknq%2BDJpgSh05D314aC%2F0T2boPDQ7cw804ou%2Fe8%2Bg%2FB4aiSZAKQNVBsoJaHwDpQyUMlBloJSBUgaqDJS3UBdB%2BS%2BUSEFtgjKGykHBJqgBFBhBhyR7oLxCgxTUjzZB%2BQElB%2FXaJqiI%2BNu8XWCpEQQBGI67r%2FvWrMZ94%2B6edKanBanI3v8KuEM1xbxC%2Fmc4H4xbFYoMaE8pBqG%2FBykupXVSyhhjrXXOee8zmUy2VC5XhiIyoCR1AqEElYLi%2BKD0n7o%2FeijS0BD17yRA%2Bec4jxFKU%2FtBUR4a%2BC4mlYBaNQYofVCJhr7LuniEUILK2Ju38vjJD2MEoUwpQaX3jy4cO7X97Ks3amhQJrV6l3LiAYC16YubL75lYyFouv3fzTvUPnwot3Tg2lNiBBCAMhfu5PUk2ITC7oWTjBGABSWlNLXrdTS0NgJ8d%2FJQ9iljAWcTWhsBLn%2B2Jh4OlKb%2BD0OxGwq7Z5YffUq0GJSW8qHYCwrR3Myp51mjxKC0IT201vLU3Tc%2BFoZiiPA%2F%2BCISGq0fPPc2Z5QAlLlw%2Fx96BQ0F2JpdffndKQEoT%2Fo%2FPNxpKETLB6588VqJQmnKv7CThpbaPXX9vTZKFIoDn6iJ%2FaEQzZ%2B49yuRhNIeKuRAAXaO7yWJEoViSmYYChuH7xujUkBFqMiHwvrR8tCPqwlBEdlMPhS2j%2B%2F91DWn1koGimwmHwob52%2Fculnp6oNfGSEoIpfJh8La7HS1S0cevrKGCWXEZtJQou2zp%2B%2B8LtE0E8qIgUwBhWj90OLtDx9NLme0DHSwqxiLfQiyQ6GK9nMAAAAASUVORK5CYII%3D&logoColor=white" /><a/>

### Installation
```shell
git clone https://github.com/eraraya-ricardo/qcnn-hep.git
cd qcnn-hep
python -m pip install -r requirements.txt
python setup.py
```
For a more detail step-by-step installation, please refer to [Docs and Tutorial](#docs-and-tutorial).

### Docs and Tutorial
- Docs: [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ojCEutBoHu-L6Q3PyWSYI51MNIr3OF_k?usp=sharing) or download [here](https://github.com/eraraya-ricardo/qcnn-hep/blob/main/assets/qcnn_drc_docs.ipynb).
- Tutorial: [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TWQgdVzKUITMNzIUFtyzq9MfuTfkyJVe?usp=sharing) or download [here](https://github.com/eraraya-ricardo/qcnn-hep/blob/main/assets/qcnn_drc_tutorial.ipynb).
