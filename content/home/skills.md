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

[[feature]]
  description:
  icon: skills/pennylane
  icon_pack: custom
  name: PennyLane
  
  icon = "pennylane"
  icon_link = "skills/"
  icon_pack = "custom"
  name = "[PennyLane](https://pennylane.ai/)"
  description = ""

[[feature]]
  icon = "qiskit"
  icon_link = "skills/"
  icon_pack = "custom"
  name = "[Qiskit](https://qiskit.org/)"
  description = ""

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
