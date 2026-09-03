# d-SEAMS

Deferred Structural Elucidation Analysis for Molecular Simulations: the
topological ice score (hexagonal and double-diamond cages on primitive
rings), CHILL and CHILL+, topology keys and key libraries, ions and
guests, for LAMMPS, GROMACS and ASE trajectories.

| component | what it is | get it |
|---|---|---|
| [seams-core](https://github.com/d-SEAMS/seams-core) | the C++ engine and the `seams` command line | [releases](https://github.com/d-SEAMS/seams-core/releases), [book](https://docs.dseams.info) |
| [PydSEAMSlib](https://github.com/d-SEAMS/PydSEAMSlib) | Python: `Frame` API, features for deeptime and PyEMMA, MDAnalysis and OVITO adapters | `pip install pydseamslib`, [docs](https://d-seams.github.io/PydSEAMSlib/) |
| [yodaStruct](https://github.com/d-SEAMS/yodaStruct) | Lua and Fennel: `require("dseams")` | [docs](https://d-seams.github.io/yodaStruct/) |
| [dseams-plumed](https://github.com/d-SEAMS/dseams-plumed) | the `DSEAMS_CAGES` PLUMED action: cage counts, ion classes, key libraries, filled cages on the fly | `pixi run build` |
| [linkcell](https://github.com/d-SEAMS/linkcell) | periodic linked-cell k-nearest neighbour search | crates.io |
| [dseams2_repro](https://github.com/d-SEAMS/dseams2_repro) | the reproducibility package of the d-SEAMS 2 paper: locked revisions, workflow, reference results | Snakemake |
| [wiki](https://wiki.dseams.info) | worked examples for every front end | |
| [dseams.info](https://dseams.info) | the suite map | |

Cite the d-SEAMS paper (Goswami, Goswami and Singh, *J. Chem. Inf. Model.* 2020) and the release tag you used; every repository carries a `CITATION.cff`.
