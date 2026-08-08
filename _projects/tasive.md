---
layout: page
title: TASIVE
description: Transformer-based Siamese network for offline signature verification.
importance: 2
category: coursework
---

TASIVE is an offline signature-verification system built around a Swin-T Siamese network, a lightweight MLP projection head, L2-normalized 128-dimensional embeddings, and a scaled cosine binary-cross-entropy objective.

The evaluation uses a strict writer-disjoint train/validation split to prevent identity leakage and a fixed all-pairs validation set of 5,748 signature pairs.

Under this protocol, TASIVE achieved 99.98% accuracy, 1.0000 ROC-AUC, and 0.0000 EER, outperforming a reproduced SigNet baseline evaluated under the same conditions.
