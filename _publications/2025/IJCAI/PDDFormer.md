---
title: "PDDFormer: Pairwise Distance Distribution Graph Transformer for Crystal Material Property Prediction"
collection: publications
category: conferences
permalink: /publication/2025/IJCAI/PDDFormer
excerpt: ''
date: 2025-04-29
venue: 'International Joint Conference on Artificial Intelligence'
paperurl: 'arxiv.org'
citation: '???, "PDDFormer: Pairwise Distance Distribution Graph Transformer for Crystal Material Property Prediction," in International Joint Conference on Artificial Intelligence, 2025.'
---

Crystal structures can be simplified as a periodic point set that repeats across three-dimensional space along an underlying lattice. Traditionally, crystal representation methods rely on descriptors such as lattice parameters, symmetry, and space groups to characterize the structure. However, in reality, atoms in materials always vibrate above absolute zero, causing their positions to fluctuate continuously. This dynamic behavior disrupts the fundamental periodicity of the lattice, making crystal graphs based on static lattice parameters and conventional descriptors discontinuous under slight perturbations. Chemists proposed the pairwise distance distribution (PDD) method to address this. However, the completeness of PDD requires defining a large number of neighboring atoms, leading to high computational costs. Additionally, PDD does not account for atomic information, making it challenging to apply it directly to crystal material property prediction tasks. To tackle these challenges, we introduce the atom-weighted Pairwise Distance Distribution (WPDD) and Unit cell Pairwise Distance Distribution (UPDD) for the first time, applying them to the construction of multi-edge crystal graphs. We demonstrate the continuity and general completeness of crystal graphs under slight atomic position perturbations. Moreover, by modeling PDD as global information and integrating it into matrix-based message passing, we significantly reduce computational costs. Comprehensive evaluation results show that WPDDFormer achieves state-of-the-art predictive accuracy across tasks on benchmark datasets such as the Materials Project and JARVIS-DFT.

