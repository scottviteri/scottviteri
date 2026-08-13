# Scott Viteri

I am a computer science PhD candidate at Stanford's Center for AI Safety. I
study how language models can produce reasoning and memory that improve their
own learning, and how reasoning systems organize knowledge. My work has moved
from formal verification and interactive theorem proving toward AI alignment,
reinforcement learning, and self-directed learning.

[Website and publications](https://scottviteri.com/)

This page is a curated map. Repositories not listed here may be research
notebooks, prototypes, old coursework, forks, or tools made for one particular
machine.

## Start here

- **[Markovian Transformers for Informative Language Modeling](https://github.com/scottviteri/MarkovianTraining)** — Code, evaluations, and artifacts for our [ICLR 2026 paper](https://openreview.net/forum?id=OMjcX1Z6Uu). The project studies reinforcement-learning objectives that reward chains of thought for being useful context for the model's own answer.

- **[Epistemic phase transitions in AI-era mathematics](https://github.com/scottviteri/ept-ai-analysis)** — A reproducible extension of my earlier work on proof-dependency networks to AI-assisted Lean corpora, including audited derived data and an [interactive report](https://scottviteri.github.io/ept-ai-analysis/).

- **[Weft](https://github.com/scottviteri/Weft)** — A tree-based interface for exploring many continuations from base language models, with token-level log-probability views and a second model that interprets what each continuation commits the text to.

## Experiments and visual work

- **[HessianAnalysis](https://github.com/scottviteri/HessianAnalysis)** — An exploratory measurement framework for asking whether independently initialized language models converge toward similar gradient, function-update, subspace, and curvature geometry during training.

- **[ouroboros](https://github.com/scottviteri/ouroboros)** — A constrained self-modification experiment: an Emacs Lisp program can rewrite both its source and the prompt that determines how it will next be rewritten, while a small external kernel preserves the experimental record.

- **[UniversalBackrooms](https://github.com/scottviteri/UniversalBackrooms)** — A multi-model recreation of the Backrooms experiment, with configurable conversational templates and example transcripts. It is the most widely used repository on this account, but its model and API assumptions are now historical.

- **[Multifractal Visualizer](https://github.com/scottviteri/multifractal-visualizer)** — A GPU-accelerated OpenGL experiment for moving between fractal systems under deterministic and probabilistic update rules.

## Current status — August 2026

- **Complete research artifact:** `MarkovianTraining` accompanies the published paper, poster, slides, evaluation code, and experimental results.

- **Active research:** `ept-ai-analysis` is an audited, reproducible analysis with a live report; follow-up work on proof grain and full unfolding is still in progress.

- **Active prototype:** `Weft` has working GUI, terminal, and library interfaces and a passing local test suite.

- **Research prototype:** `HessianAnalysis` has functional training and plotting tools plus documented metrics, but not yet benchmark results, a paper, or a stable API.

- **Early experiment:** `ouroboros` has a documented kernel, published lineage, and explicit containment model; its scientific value is still exploratory.

- **Historical but runnable:** `UniversalBackrooms` is preserved as an experiment and collection of transcripts rather than advertised as a current multi-provider library.

- **Visual prototype:** `multifractal-visualizer` is a working research sketch with build documentation, not a supported cross-platform application.

## Older work worth browsing

- **[Exploring the Space of Short Programs](https://github.com/scottviteri/ExploringTheSpaceOfShortPrograms)** — Patterns in very short programs built from the universal iota combinator.

- **[ManipulateProofTrees](https://github.com/scottviteri/ManipulateProofTrees)** — Tools for extracting and analyzing the tree structure of Coq proof objects.

- **[What Is Music?](https://github.com/scottviteri/WhatIsMusic)** — An older computational attempt to characterize harmony from first principles.

## How to read this account

I use four status words deliberately: **complete** means a finished research
artifact, **active** means I am still changing the work, **prototype** means the
idea is clearer than the package, and **historical** means the repository is
preserved but not maintained.

My publication rule is that a public repository must be safe to expose and
possible for a stranger to interpret. A repository is featured only when it
also has a useful entry point, an honest status, and some evidence that it
works. Personal data, machine-specific state, and unreleased research stay
private; superseded public work is archived rather than silently hidden.
