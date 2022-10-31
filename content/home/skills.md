---
# An instance of the Featurette widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: features

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 5

design:
  spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
    padding: ["20px", "0", "20px", "0"]
  columns: 4
    # this is a custom setting with the custom features.html
    # select the number of columns, default is 3
    
title: Skills
subtitle:

# Showcase personal skills or business features.
# - Add/remove as many `feature` blocks below as you like.
# - For available icons, see: https://wowchemy.com/docs/page-builder/#icons
feature:
- description:
  icon: skills/pennylane
  icon_pack: custom
  name: PennyLane
- description:
  icon: skills/qiskit
  icon_pack: custom
  name: Qiskit
- description:
  icon: skills/cirq
  icon_pack: custom
  name: Cirq
- description:
  icon: skills/qutip
  icon_pack: custom
  name: QuTiP
- description:
  icon: skills/tfq
  icon_pack: custom
  name: TensorFlow Quantum
- description:
  icon: skills/tensorflow
  icon_pack: custom
  name: TensorFlow
- description:
  icon: skills/keras
  icon_pack: custom
  name: Keras
- description:
  icon: skills/pytorch
  icon_pack: custom
  name: PyTorch
- description:
  icon: skills/scikitlearn
  icon_pack: custom
  name: scikitlearn
- description:
  icon: skills/opencv
  icon_pack: custom
  name: OpenCV
- description:
  icon: skills/python
  icon_pack: custom
  name: Python
- description:
  icon: skills/cplusplus
  icon_pack: custom
  name: C++
#- description:
#  icon: skills/c
#  icon_pack: custom
#  name: C

# Uncomment to use emoji icons.
#- icon: ":smile:"
#  icon_pack: "emoji"
#  name: "Emojiness"
#  description: "100%"  

# Uncomment to use custom SVG icons.
# Place custom SVG icon in `assets/images/icon-pack/`, creating folders if necessary.
# Reference the SVG icon name (without `.svg` extension) in the `icon` field.
#- icon: "your-custom-icon-name"
#  icon_pack: "custom"
#  name: "Surfing"
#  description: "90%"

active: true

---
