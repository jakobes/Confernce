### Computational Modeling of Bacterial Dynamics

# Authors

Karitk Jain, Christoph Lohrmann, Christian Holm

# Affiliation

Institute for Computational Physics, University of Stuttgart, Allmandring 3, 70569 Stuttgart

# Abstract

Microorganisms namely bacteria can propel, proliferate and form aggregations in a number
of media, and they exhibit interesting behavior under shear flow field. In addition to being self-
propelled, some bacteria can adhere to each other and to surfaces where they can create fast
growing colonies, called biofilms. Extensive research efforts focus on understanding of the life cycle
of a biofilm i.e. ranging from collective bacterial dynamics to biofilm formation and its depletion.
Biofilm research has applications in various fields like biology, medicine and engineering. Studies
have demonstrated that bacteria more commonly accumulate at surfaces and around obstacles that
they encounter in their propulsion path. The initiation, growth and decline of a biofilm depends
largely on the flow field and forces that are acting on them.
Computational modeling has evolved as an important tool for the study of physical and biological
phenomena whereby mathematical models of a process are developed and studied using simulations
on computers. In this work, we developed a model to study the dynamics of Escherichia Coli
(E. Coli) bacteria to study their growth, replication, adherence to surfaces under shear flow. In
the model the bacteria are represented by molecular dynamics (MD) particles while the fluid is
represented by a lattice Boltzmann method (LBM). The MD particles are coupled to the LB
fluid using a frictional point coupling that ensures momentum conservation of the total system.
We present collective transient dynamics of up to 4000 bacteria in confined geometries with and
without external flow. All the simulations are performed on one GPU using the ESPResSo package
for soft matter, each requiring about 108 hours of execution time. Our results show ephemeral
accumulation of bacteria around obstacles, and their tendency to undergo a momentary stasis in
the regions of flow recirculations. We further model bacterial replication whereby one bacterium
replicates to about 2 16 dynamically in the simulation to form a large colony, which, under the
effect of shear forces washes away eventually. The model is currently being parametrized using
experimental data and ongoing research will include application of this model to study microbial
growth under gradients of nutrition.
