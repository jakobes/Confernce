# A Lattice-Boltzmann-Immersed Boundary technique for computing the vascular journey of micro-particles

## Abstract

Micro and nano–particles are systemically injected as drug carriers to specifically
deliver therapeutics into diseased tissue. Their vascular journey and adhesion mechanics
are key ingredient to optimize strategies mainly against cancer and cardiovascular
disorders. Computational methods are crucial to deep understand the vascular transport of
platelets-like objects due to the large number of parameters involved. Particles can be
precisely tailored in term of their shape, size, superficial properties and stiffness
(the so called 4S parameters) to modulate their abilities, so that, the number of paths
toward the optimization uncontrollably grows. The recipe for efficient micro- and
nano-carriers, in particular, is far from being discovered and computational model are
useful tools for the design of such constructs. Indeed, reliable computational schemes
must account for the transport of several structures with different stiffness, densities,
shapes, and need to model particle-particle and particle-walls interactions.  Here, a
kinematic/dynamics hybrid Immersed–Boundary (IB)/Lattice Boltzmann (LB) scheme is
proposed. Coclite et al. (2019) Precisely, the IB technique is employed in its kinematic
formulation for the red blood cells in order to save computational time. Red cell
membranes are considered here as dense as plasma, so that, the membranes velocity is
advected with the withstanding fluid velocity. On the contrary, microparticles are
transported with the dynamics IB formulation developed and validated by the author.
Coclite et al. (2018, 2019) Both, cells and microcarriers are modeled as a collection of
mass-spring elements responding to a bending potential, a worm-like chain potential and
the area conservation constraint. Furthermore, on particles’ surfaces are uniformly
distributed adhesive molecules (ligands) interacting with their counterpart (receptors)
disposed on vascular walls.

References
A. Coclite, S. Ranaldo, M.D. de Tullio, P. Decuzzi, and G. Pascazio. Kinematic
and dynamic forcing strategies for predicting the transport of inertial capsules via a
combined lattice boltzmann immersed boundary method. Computers & Fluids, 180:
41–53, 2019. ISSN 0045-7930. doi: https://doi.org/10.1016/j.compfluid.2018.12.014.
A. Coclite, G. Pascazio, M.D. de Tullio, and P. Decuzzi. Predicting the vascu-
lar adhesion of deformable drug carriers in narrow capillaries traversed by blood
cells. Journal of Fluids and Structures, 82:638 – 650, 2018. ISSN 0889-9746. doi:
https://doi.org/10.1016/j.jfluidstructs.2018.08.001.
