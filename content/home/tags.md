---
# An instance of the Tag Cloud widget.
# Docs: https://wowchemy.com/docs/page-builder/
widget: tag_cloud

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 120

title: Popular Topics
subtitle: ''

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

content:
# Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy: tags
  # Choose how many tags you would like to display (0 = all tags)
  count: 20
design:
  # Minimum and maximum font sizes (1.0 = 100%).
  font_size_min: 0.7
  font_size_max: 2.0
---
