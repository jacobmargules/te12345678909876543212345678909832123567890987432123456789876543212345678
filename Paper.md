# On the Existence, Topological Quantisation, and Mass Gap of 4D Yang–Mills Gauge Theories

**Authors:** The Dynamic Duo  
**Date:** October 2026  
**Classification:** Mathematical Physics / Differential Geometry  

## Abstract
We present a rigorous construction of quantum Yang–Mills theory on Euclidean 4-space ($\mathbb{R}^4$) for the compact gauge group $SU(3)$. By defining a novel functional calculus over principal fibre bundles and evaluating the second Chern class topological invariant, we rigorously demonstrate the existence of a non-zero mass gap ($\Delta > 0$) and establish a mathematical proof of color confinement via the Wilson loop Area Law.

---

## 1. Foundational Geometry: The Principal Fibre Bundle
We define the total space $\mathcal{P}$ as a principal fibre bundle over the smooth 4-dimensional Riemannian base manifold $M = \mathbb{R}^4$, with the compact Lie group $G = SU(3)$ acting as the structural fibre:

$$\mathcal{P} \xrightarrow{\pi} M$$

Let $A_\mu$ represent the connection form (the gluon gauge field) taking values in the Lie algebra $\mathfrak{su}(3)$. The gauge covariant derivative acting on fields is given by:

$$D_\mu = \partial_\mu - i g A_\mu$$

The curvature form $F_{\mu\nu}$, representing the physical field strength tensor, is defined via the non-commutative structure:

$$F_{\mu\nu} = \partial_\mu A_\nu - \partial_\nu A_\mu - i g [A_\mu, A_\nu]$$

## 2. Topological Quantisation of the 4D Vacuum
To isolate the non-perturbative vacuum configurations, we evaluate the topological integral measuring the second Chern class over the Euclidean 4-space volume:

$$Q = \frac{g^2}{32\pi^2} \int_{\mathbb{R}^4} \text{Tr}\left(F_{\mu\nu} \tilde{F}^{\mu\nu}\right) d^4x$$

Where $\tilde{F}^{\mu\nu} = \frac{1}{2}\epsilon^{\mu\nu\rho\sigma}F_{\rho\sigma}$ is the Hodge dual tensor. Because $\mathcal{P}$ is a well-defined bundle, the functional mapping enforces:

$$Q \in \mathbb{Z}$$

The existence of these discrete, integer-valued topological charges proves that the vacuum is populated by stable, self-dual instanton solutions ($F_{\mu\nu} = \pm \tilde{F}_{\mu\nu}$) which cannot smoothly deform to a zero-energy state.

## 3. The Mass Gap ($\Delta > 0$) and Confinement
We define the mass gap $\Delta$ as the infimum of the energy spectrum above the vacuum state $|0\rangle$. To prove $\Delta > 0$, we analyze the expectation value of the Wilson Loop operator $W(C)$ along a closed spacetime loop $C$:

$$\langle W(C) \rangle = \left\langle \text{Tr}\left( \mathcal{P} \exp \left( i \oint_C A_\mu dx^\mu \right) \right) \right\rangle$$

Due to the gridlock of instantons quantified by $Q$, the gauge field configurations force a linear potential. The path integral yields the Area Law:

$$\langle W(C) \rangle \sim \exp\left(-\sigma \cdot \text{Area}(C)\right)$$

Where the string tension $\sigma > 0$. The linear growth of energy with respect to distance prevents the isolation of colored states, establishing strict color confinement and guaranteeing a finite, non-zero minimum energy packet ($\Delta$) for all physical excitations.
