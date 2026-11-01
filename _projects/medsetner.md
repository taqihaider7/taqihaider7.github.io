---
layout: page
title: MedSETNER
description: Medical dataset-name extraction from scientific literature.
img: assets/img/medsetner.svg
importance: 1
category: research
permalink: /portfolio/medsetner/
---

## Research question

How can dataset names be identified reliably in medical research papers?

## My work

For my master's research at Novosibirsk State University, I led corpus development and annotation across **691 articles** containing **9,376 dataset-name mentions**. Inter-annotator agreement was Fleiss' κ = 0.85.

I compared rules, CRF, SciBERT, ModernBERT, BiomedBERT, and GLiNER2 using article-level splits and a separate 151-article out-of-distribution test set. BiomedBERT achieved mean exact-span F1 of **60.7%** on same-pool data and **60.8%** on the out-of-distribution set.

The paper was accepted at AIST 2026, CCIS track. See the [publication details](/publications/).
