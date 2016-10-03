Z2Pack
automates the calculation of topological numbers of band-structures.
If works with first-principles calculations (z2pack.fp),
tight-binding models (z2pack.tb) and explicit Hamiltonian matrices (z2pack.hm).

The topological numbers are computed from the evolution of Wannier charge
centers (WCC), as described in 
[this paper](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.83.235401)
for the case of the Z2 invariant.

The WCC are calculated from overlap matrices which are calculated 
either directly (for tb) or via the Wannier90 code package (fp).

- Documentation: <http://z2pack.ethz.ch/doc>
- Online interface: <http://z2pack.ethz.ch/online>

[![Build Status](https://travis-ci.org/Z2PackDev/Z2Pack.svg?branch=dev%2Fcurrent)](https://travis-ci.org/Z2PackDev/Z2Pack)
