---
name: multimodal-reflection-critic
description: Analyzes pre- and post-action screen states to verify execution success, detect stall loops, and guide recovery actions.
license: Apache-2.0
---

# Multimodal Reflection Critic

## Overview
This skill evaluates visual differentials between consecutive screen states, verifying whether dispatched UI actions attained their expected outcomes.

## Capabilities
- Detects whether a page transition, modal popup, or input focus change occurred.
- Diagnoses failed interactions (e.g., misclicks, unhandled permissions, network errors).
- Triggers backtracking and adaptive re-planning when an interaction stalls.
