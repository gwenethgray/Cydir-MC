# Cydir-MC
Monte Carlo model of Cytoskeleton Dynamic Instability and Repair (CyDIR) kinetics in multicompartmental cell geometry.

Implementation goals for CyDIR-MC:
- Mixed parallel/antiparallel alignment of microtubule plus tips
- Cleaving by severin, katanin, and spastin
- Actin and intermediate filaments, stabilization rules, ensconsin modulation, and cortical actin mesh
- Multidirectional microtubule networks
- Read radiation damage files from TOPAS-nBio
- Translate CyDIR-MC cell and molecule models into Geant4 objects and vice versa
- Transport proteins (dynein, kinesin), dynamic local tubulin availability
- Stable diffuse microtubule motion to make room for new growth
- Intercompartmental transport
- Dynamic neurite compartment geometry coupled with incoming and outgoing membrane potentials (NEURON/BMTK)
