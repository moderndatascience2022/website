---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: blank # See https://wowchemy.com/docs/page-builder/
headless: true # This file represents a page section.
weight: 35 # Order that this section will appear.
title: Speakers
subtitle: ''
design:
  background:
    # image: backgrounds/spotlight.webp
    # text_color_light: true
  spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
    padding: ['20px', '0', '20px', '0']
  columns: '1'
  css_class: fullscreen
---

<!-- DAY 1 -->
{style="padding-top: 5rem"}

{{< table path="speakers.csv" header="true" >}}
