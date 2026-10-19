---
title: "Multimodal Humor Detection in Videos via Domain-Specific Representations and Deep Hybrid Fusion Networks"
authors: "<strong>Jamuna S. Murthy</strong>, G. M. Siddesh"
collection: publications
permalink: /publication/humor_detection_dhf
date: 2026-09-21
venue: 'Soft Computing (Springer Nature)'
figure: 'humor_detection_dhf.jpg'
excerpt: 'Humor in videos is hard to detect because cues are spread across text, visuals, and audio that are misaligned in time, imbalanced, and noisy. This framework combines Domain-Specific Representation Learning, which separates modality-invariant and modality-specific features with a Bi-LSTM, and a Deep Hybrid Fusion network that merges them through cross-modal attention with suppression, reaching up to 95.8% accuracy on IEMOCAP, CMU-MOSI, and CMU-MOSEI.'
---

Multimodal data analysis plays a pivotal role in understanding human-centric content by integrating text, visual, and audio cues. Humor detection in videos remains particularly challenging because of temporal misalignment across modalities, data imbalance, and noise in real-world signals.

The proposed framework combines **Domain-Specific Representation Learning (DSRL)** with a **Deep Hybrid Fusion (DHF)** network. Text is encoded with an enhanced BERT, images with HOG and ResNet-50 features, and audio with LPCC features and recursive feature elimination. The Bi-LSTM-based DSRL module disentangles modality-invariant and modality-specific features, and DHF integrates them through self-attention and cross-modal attention with suppression mechanisms, trained with task, difference, similarity, and reconstruction losses.

Experiments on IEMOCAP, CMU-MOSI, and CMU-MOSEI show that the model outperforms state-of-the-art baselines, reaching up to **95.8% accuracy**. Ablation studies and precision–recall analyses confirm the robustness and efficiency of the framework, and the paper discusses ethical considerations and deployment challenges for real-world humor recognition.

Received 29 July 2024 · Accepted 21 September 2026.
