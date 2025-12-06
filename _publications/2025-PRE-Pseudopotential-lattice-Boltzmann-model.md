---
title: "Pseudopotential lattice Boltzmann model with tunable coexistence densities and no interfacial velocity slip"
collection: publications
category: manuscripts
permalink: /publication/2025-PRE-Pseudopotential-lattice-Boltzmann-model
excerpt: 'We proposed a pseudopotential model that can achieve thermodynamic consistency and does not suffer from interfacial velocity slip.'
date: 2025-08-28
venue: '<b>Physical Review E</b>'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://houjunren-thu.github.io/files/2025-PRE-Pseudopotential-lattice-Boltzmann-model.pdf'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: '<b>Hou J</b>, Jiang S, Ma Y, et al. Pseudopotential lattice Boltzmann model with tunable coexistence densities and no interfacial velocity slip[J]. Physical Review E, 2025, 112(2): 025312.'
---
The pseudopotential model in lattice Boltzmann method is widely used to simulate two-phase flows. Thermodynamic consistency is an important issue in the pseudopotential model. To achieve thermodynamic consistency, various force schemes have been proposed for the pseudopotential model. However, their performance under transient and moving conditions remains insufficiently validated. We evaluate existing force schemes and find that most of them suffer from interfacial velocity slip. A Chapman-Enskog analysis reveals that these schemes introduce error terms in the macroscopic equations, leading to the interfacial velocity slip. While other schemes avoid this slip, they fail to achieve thermodynamic consistency. To address this issue, we propose a novel pseudopotential model achieving thermodynamic consistency while preventing interfacial velocity slip. Our model introduces a new pseudopotential force by adding a term \\( 2\gamma \nabla^2\psi \nabla\psi + O(\nabla^5) \\) to the original force. Here, \\( \psi \\) represents the pseudopotential and the coefficient \\( \gamma \\) is used to tune the coexistence densities. The applicability of our model under moving conditions is validated through simulations of two-phase Couette flow and two-phase Poiseuille flow. Numerical results confirm that our model achieves second-order accuracy. The transient results of our model are compared with those of volume of fluid method, validating the applicability of our model under transient conditions. Finally, droplet splashing and liquid film evaporation under shear flow are also simulated to demonstrate our model's capability for simulating two-dimensional flow and interphase mass transfer.
