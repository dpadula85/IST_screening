Description
===========
This repository contains electronic supporting information for the paper
**Identification of New Inverted Singlet-Triplet Cores by High-Throughput
Virtual Screening**, submitted to _ChemRxiv_ by O. H. Omar, X. Xie, A. Troisi,
and D. Padula.

Each subfolder contains files for the various simulations reported
in the paper.

If using data from this paper, please acknowledge our work.

For assistance or questions, please do contact authors at email addresses
provided for the paper.

- CSD subset: data regarding the molecules derived from the CSD

- ZINC subset: data regarding the molecules derived from ZINC

- TD_opt_candidates: $S_1$ and $T_1$ TDDFT/M06-2X/def2-TZVP optimised geometries. 

Within each subset folder: 

- MAIN: the merged database of molecules with TDDFT $\Delta E_{ST} < 0.5$ eV, and their $n_{rots}$ and $K_{HL}$ values.

- dr: $\Delta r$ metric by [Guido](https://pubs.acs.org/doi/abs/10.1021/ct400337e) for the molecules checked.

- CAS_a_b - computed vertical $S_1$ and $T_1$ energies (and $\Delta E_{ST}$) at the CASSCF/6-31G* level with Gaussian. 
