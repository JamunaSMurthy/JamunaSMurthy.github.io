---
title: "Controlla: Learning Controllability via Graph-Constrained Latent Geometry"
authors: "<strong>Jamuna S. Murthy</strong>, Amin Karimi Monsefi, Rajiv Ramnath"
collection: publications
permalink: /publication/controlla
date: 2026-09-25
venue: 'NeurIPS 2026 — Conference on Neural Information Processing Systems'
paperurl: 'https://arxiv.org/abs/2605.16603'
figure: 'controlla.jpg'
project: 'https://jamunasmurthy.github.io/controlla-affecthuman/'
excerpt: 'Controllable multimodal generation is usually posed as inference-time conditioning, which leaves unstructured how semantic attributes evolve and invites identity drift. Controlla instead treats controllability as a property of latent geometry: it learns identity and attribute factors from multimodal inputs and aligns them with graph priors through graph-constrained optimal transport, so attributes follow graph-consistent trajectories while reference identity is preserved. The paper also contributes AffectHuman-43K, a leakage-aware multimodal benchmark.'
---

Controllable multimodal generation is commonly formulated as an inference-time conditioning problem — prompts, guidance, or auxiliary modules — which does not explicitly structure how semantic attributes evolve and can lead to identity drift and inconsistent cross-modal behavior. Controlla is a modular factorized-control framework that treats controllability as a property of structured latent geometry. It maps image, reference image, text, and audio into factorized identity and attribute spaces, and aligns these factors with identity and affective graph priors using graph-constrained optimal transport, so attribute edits follow graph-consistent trajectories while the reference identity is held stable.

To evaluate this setting the paper introduces **AffectHuman-43K**, a leakage-aware, identity-disjoint multimodal benchmark for reference-grounded affective control, together with geometry-aware metrics for trajectory smoothness, graph consistency, and identity–attribute disentanglement. Experiments show consistent improvements in controllability, identity preservation, and cross-modal alignment.
