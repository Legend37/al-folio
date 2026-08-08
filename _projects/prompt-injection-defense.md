---
layout: page
title: Inference-Time Defense Against Prompt Injection
description: Detecting intent drift in tool-using language-model agents.
importance: 1
category: research
---

This research develops a non-intrusive inference-time defense for indirect prompt injection in LLM agents. The method detects intent drift between hidden states before tool calls and after tool responses.

The experimental pipeline uses a Qwen3-8B tool-calling agent, hooks over the final four transformer layers, paired clean and injected trajectories, cosine and contrastive probes, and automatic attack-success labeling.

Evaluation covers a 1,220-task base benchmark and a 4,000-case cross-domain suite spanning ten application domains, including task, user-tool, attacker, and cross-dataset generalization. Injection generation and genetic search explore a 3,072-configuration strategy space. A first-author manuscript is under submission.
