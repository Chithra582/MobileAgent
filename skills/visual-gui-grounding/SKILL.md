---
name: visual-gui-grounding
description: Localizes interactive UI widgets, text labels, and graphic icons from screen images into precise click coordinates.
license: Apache-2.0
---

# Visual GUI Grounding

## Overview
This skill processes raw screenshots through OCR and multimodal vision-language models to extract bounding boxes and interactive target coordinates.

## Capabilities
- Detects textual labels and numeric values using high-accuracy OCR.
- Identifies icon semantics without relying on system accessibility hierarchies.
- Computes normalized and absolute $(x, y)$ target coordinates for input dispatch.
