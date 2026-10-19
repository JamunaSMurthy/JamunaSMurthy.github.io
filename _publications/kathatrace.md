---
title: "KathaTrace: Diagnosing Semantic Trajectory Collapse in Generated Visual Narratives"
authors: "<strong>Jamuna S. Murthy</strong>, Amin Karimi Monsefi, Rajiv Ramnath"
collection: publications
permalink: /publication/kathatrace
date: 2026-07-01
venue: 'Under submission to a CORE A* venue · arXiv preprint'
paperurl: 'https://arxiv.org/abs/2607.01312'
figure: 'kathatrace.jpg'
project: 'https://jamunasmurthy.github.io/kathatrace/'
excerpt: 'Recent story generators produce visually coherent image sequences, but coherence does not guarantee that the transition meaning of the source story survives. KathaTrace is a generator-agnostic protocol for diagnosing semantic trajectory collapse, evaluating each transition under text-only, image-only and text-plus-image evidence. It contributes KathaBench-25K and defines the Semantic Trajectory Gap, the transition meaning lost during visualisation.'
---

Visual narratives are central to storyboards, comics, children's media, and film previsualization, where viewers must understand a story from images alone. Story generators such as StoryDiffusion produce coherent sequences, but visual coherence does not guarantee that the source story's transition meaning remains recoverable. KathaTrace is a generator-agnostic protocol for diagnosing this failure — *semantic trajectory collapse* — by evaluating each transition under three evidence conditions (text-only, image-only, and text+image) and filtering ambiguous items.

The paper contributes **KathaBench-25K**: 5,000 narratives from classical collections (Aesop, Panchatantra, Kathasaritsagara), 20,000 transitions, and 28,712 recoverability questions. It defines the **Semantic Trajectory Gap (STG)** as text-only minus image-only recoverability — the transition meaning lost during visualization. Human validation yields Fleiss' κ = 0.845, and state-of-the-art generators show a substantial STG (23.5 ± 1.3). **Semantic Compass**, an actionability probe, uses KathaTrace signals for post-generation repair and improves storyboard selection.
