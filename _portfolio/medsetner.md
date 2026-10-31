---
title: "MedSETNER"
collection: portfolio
order: 1
category: "Research · NLP"
excerpt: "A benchmark corpus for extracting medical dataset names from scientific literature."
outcome: "Accepted at AIST 2026"
---

## Research question

How can dataset names be identified reliably in medical research papers?

## Work

For my master's research at Novosibirsk State University, I led corpus development and annotation across 691 articles containing 9,376 dataset-name mentions. Inter-annotator agreement was Fleiss' κ = 0.85.

I compared rules, CRF, SciBERT, ModernBERT, BiomedBERT, and GLiNER2 using article-level splits and a separate 151-article out-of-distribution test set. BiomedBERT achieved mean exact-span F1 of 60.7% on same-pool data and 60.8% on the out-of-distribution set.

## Status

The paper, _MedSETNER: A Benchmark Corpus for Extracting Dataset Names from Medical Scientific Literature_, was accepted at AIST 2026. See the [publication details](/publications/).
