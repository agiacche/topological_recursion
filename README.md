# Topological recursion

Around 2007, B. Eynard, N. Orantin and L. Chekhov discovered a recursion formula, called topological recursion, while working on random matrix theory. This recursion formula has appeared in many different fields as enumerative geometry, intersection theory on the moduli space of curves, integrable systems, topological strings, quantum field theories, matrix models and knot theory.

The topological recursion associates a doubly indexed family of differential forms $\omega_{g,n}$ to a spectral curve $\mathcal{S}$, which consists of a Riemann surface with some initial data: $$\mathcal{S}\xrightarrow{\quad\text{TR}\quad}(\omega_{g,n})_{2g-2+n>0}$$

## BE topological recursion
The BE_TopologicalRecursion.nb code computes the above differential, given a spectral curve as initial data. The code allows for computations in the Bouchard–Eynard setting, that is for spectral curves with higher ramifications.

## Airy structures
The code Airy_structures.nb computes Airy structure correlators, that are an algebraic reformulation of topological recursion. The initial data are (A,B,C,D) tensors in the sense of Kontsevich–Soibelman.

## Cut-and-join
In many cases, topological recursion is equivalent to a cut-and-join equation. If available, the cut-and-join recursion is much faster than the usual topological recursion formula. The code WK_BGW_cut_and_join.nb computes the Witten–Kontsevich partition function and the Brezin–Gross–Witten partition function using the cut-and-join formalism.
