---
title: Phenotypic Interpretation 2.0
author:
- name: Eric J. Ma
- affiliation: MIT Biological Engineering
---

# Bio

> - Final year PhD candidate at MIT Biological Engineering
> - Advisor: Jonathan A. Runstadler
> - Computational disease ecology and applied machine learning
> - On a mission to make disease surveillance a **quantitative** and **predictive** endeavour.

# Phenotypic Interpretation

##

![This goal is hampered by lack of systematic measurements and inability to pre-emptively phenotype viruses ahead-of-time.](./figures/genomic-interpretation-to-policy.jpg){#fig .class height="350px"}

## The Need

> 1. Systematic drug resistance data matched with protein sequences.
> 1. Prediction system capable of delivering interpretable insights.
> 1. A model-guided feedback loop for improving predictions and guiding pre-emptive testing.

## Proposed Solutions

> 1. High Throughput Viral Phenotyping
> 1. Interpretable Machine Learning Systems
> 1. Generative Mapping of Sequence-Fitness Landscapes

# Aim 1: HT Viral Phenotyping

## Big Goal

Biochemically **phenotype** every **viral protein** variant sampled

## Scoped Goal

Determine **drug resistance** of every **influenza neuraminidase** variant sampled

## Required Components

![](./figures/key-components.jpg)

## Rational Protein Library Generation

![Generate all known neuraminidase variants using microarray DNA synthesis. Barcoding enables arrayed amplification.](./figures/experimental-workflow-part1.jpg)

## High Throughput Cloning

![Dial-out PCR using barcodes as primers enables arraying of neuraminidase variants in 96-well format.](./figures/experimental-workflow-part2.jpg)

## High Throughput Phenotyping

![IC<sub>50</sub> measurements using viral-like particles, with uncertainty modelled using Bayesian estimation.](./figures/experimental-workflow-part3.jpg)

# Aim 2: Interpretable Geno-Pheno

## Big Goal

Deploy **machine learning** algorithms to interpretably learn **phenotype from genotype**.

## Scoped Goal

Investigate **graph convolutions** as an interpretable method for learning **drug resistance from systematic measurements**.

## Graph Convolutions

![](./figures/convolution.jpg)

## Protein Structure Graphs

- Protein structure represented as graphs
    - Nodes: Amino acids
    - Edges: Biochemical interactions

## Graph Convolutions Enable Data Introspection

![Deep learning on graphs automatically learned amino acid interactions responsible for phenotype.](./figures/most-activating.jpg)

# Aim 3: Generative Embeddings

## Big Goal

Map sequence landscape of **every viral protein** w.r.t. **quantitative phenotype**.

## Scoped Goal

Map sequence landscape of every **neuraminidase** w.r.t **drug resistance phenotype**.

## Fitness Mappings from Variational Autoencoders

![2D temporal embedding of H3N2 HA sequence evolution reveals peaks and valleys in sequence evolution.](./figures/embedding-h3n2.jpg)

# Potential Interfaces

> - Mapping drug resistance vs. sequence landscapes
> - Intelligently navigate evolvable protein search space
> - Pre-emptive testing for drug resistance

# Vision

![Quantitative and pre-emptive risk determination on a matrix.](./figures/summary-figure.jpg)


# Acknowledgments

![](./figures/runlab-logo.png){#fig .class width="400px"}

- Jonathan A. Runstadler, PhD, DVM (MIT)
- Mark Bathe, PhD (MIT)
- Jukka-Pekka Onnela, PhD (HSPH)
- David K. Duvenaud (Harvard, U Toronto)
- Islam T. Hussein, PhD, DVM (MIT)
- Nichola J. Hill, PhD (MIT)
