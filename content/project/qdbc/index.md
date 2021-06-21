---
title: "Quantum Distance-based Classifier"
date: 2020-10-22
summary: This is a code implementation of distance-based classifier (similar to k-nearest neighbour algorithm) using quantum computer adapted from research paper [\"Implementing a distance-based classifier with a quantum interference circuit\"](https://iopscience.iop.org/article/10.1209/0295-5075/119/60002) by Maria Schuld, Mark Fingerhuth, and Francesco Petruccione.
draft: false
featured: false
tags:
  - Quantum Machine Learning
external_link: ""
links:
  - url: https://github.com/Quantum-Minds/Quantum-Hacktoberfest20/blob/main/quantum%20ML/Quantum%20Distance-based%20Classifier/Quantum%20Distance-based%20Classifier.ipynb
    name: GitHub
    icon_pack: fab
    icon: github
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: true
---
This is a code implementation of distance-based classifier (similar to k-nearest neighbour algorithm) using quantum computer adapted from research paper [\"Implementing a distance-based classifier with a quantum interference circuit\"](https://iopscience.iop.org/article/10.1209/0295-5075/119/60002) by Maria Schuld, Mark Fingerhuth, and Francesco Petruccione. In this code I would not explain too many things to keep it clear and concise, please read the research paper if you would like to know the details (spoiler: the paper is so well written and easy to understand for anyone having some basics in quantum computation).
<br>
I found the modern Qiskit rewrite of the original code from the author [here](https://github.com/markf94/ibmq_code_epl_119_60002/blob/master/qiskit_distance_based_classifier.py). From my understanding, that code implementation is built specifically based on the datapoints used in the paper. So I decided to create a new one (this code) that can be implemented using any datapoints from the Iris dataset.
<br>
Goal of this code:<br>
Take any three datapoints from the datasets and use two of them as training input, then we would like to predict the label/class of the third one (testing input) using the quantum version of distance-based classifier.
