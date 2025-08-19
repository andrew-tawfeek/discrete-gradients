# Discrete Gradients

A computational framework for studying discrete Morse theory on simplicial complexes using SageMath.

## Overview

This repository contains SageMath worksheets implementing algorithms for discrete gradient vector fields, acyclic matchings, and their connections to spectral properties of combinatorial Laplacians. The code explores the relationship between:

- Discrete Morse theory and simplicial complex topology
- Acyclic matchings as discrete gradient vector fields
- Spectral coefficients of even Laplacian operators
- Rooted forests and spanning tree enumeration
- Pseudomanifold properties and normal complexes

## Core Components

**`discrete-gradients.sws`** - Main implementation of discrete gradient algorithms, including acyclic matching enumeration and Morse vector computations.

**`morse-simplicial-complex.sws`** - Morse complex construction from graph spanning trees, system of distinct representatives (SDR) analysis, and bridging operations between graphs.

**`pseudomanifolds.sws`** - Tools for pseudomanifold verification, normality checking, and gradient-forest correspondence testing.

**`rooted-forests.sws`** - Spanning forest enumeration and root system analysis for simplicial complexes.

**`hodge.sws`** - Reserved for Hodge theory implementations.

## Key Algorithms

- **Acyclic Matching Enumeration**: Computation of all discrete gradient vector fields on a simplicial complex
- **Morse Vector Analysis**: Critical cell counting and Euler characteristic verification
- **Laplacian Spectral Analysis**: Even Laplacian characteristic polynomial computation
- **Forest-Root Correspondence**: Bijective mappings between rooted forests and gradient matchings

## Mathematical Context

This work investigates discrete analogues of smooth Morse theory, particularly the correspondence between discrete gradient vector fields (represented as acyclic matchings on the Hasse diagram) and spectral properties of discrete Laplacian operators. The code implements computational verification of conjectures relating gradient counts to characteristic polynomial coefficients.

## Requirements

- SageMath 9.0+
- Standard Sage topology and graph theory modules

## Usage

Load worksheets directly in SageMath or Jupyter with the Sage kernel:
```sage
load('discrete-gradients.sws')
```

## Research Applications

Suitable for computational experiments in:
- Discrete Morse theory
- Topological data analysis  
- Spectral graph theory
- Combinatorial algebraic topology

---
*Implementation of discrete gradient vector field algorithms for topological and spectral analysis.*
