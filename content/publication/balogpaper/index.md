---
title: A Formalisation of the Balog–Szemerédi–Gowers Theorem in Isabelle/HOL
authors:
- Angeliki Koutsoukou-Argyraki
- Mantas Bakšys
- Chelsea Edmonds
date: '2023-01-01'
publishDate: '2023-12-12T16:39:33.377139Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 12th ACM SIGPLAN International Conference on Certified
  Programs and Proofs*'
doi: 10.1145/3573105.3575680
abstract: We describe our formalisation in the interactive theorem prover Isabelle/HOL
  of the Balog–Szemerédi–Gowers Theorem, a profound result in additive combinatorics
  which played a central role in Gowers’s proof deriving the first effective bounds
  for Szemerédi’s Theorem. The proof is of great mathematical interest given that
  it involves an interplay between different mathematical areas, namely applications
  of graph theory and probability theory to additive combinatorics involving algebraic
  objects. This interplay is what made the process of the formalisation, for which
  we had to develop formalisations of new background material in the aforementioned
  areas, more rich and technically challenging. We demonstrate how locales, Isabelle’s
  module system, can be employed to handle such interplays in mathematical formalisations.
  To treat the graph-theoretic aspects of the proof, we make use of a new, more general
  undirected graph theory library developed by Edmonds, which is both flexible and
  extensible. In addition to the main theorem, which, following our source, is formulated
  for difference sets, we also give an alternative version for sumsets which required
  a formalisation of an auxiliary triangle inequality. We moreover formalise a few
  additional results in additive combinatorics that are not used in the proof of the
  main theorem. This is the first formalisation of the Balog–Szemerédi–Gowers Theorem
  in any proof assistant to our knowledge.
tags:
- probabilistic method
- Isabelle/HOL
- graph theory
- proof assistant
- additive combinatorics
- interactive theorem proving
- formalisation of mathematics
links:
- name: URL
  url: https://doi.org/10.1145/3573105.3575680
---
