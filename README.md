# DFTB Mono- and Bimetallic AgAu Cluster Slater-Koster Files

This repository contains ground state (GS) and excited state (ES) Slater-Koster parameter files in DFTB+ format for monometallic and bimetallic silver-gold (Ag-Au) clusters.

## 📁 File Structure:
- **GSSK/** – Ground state Slater-Koster files
- **ESSK/** – Excited state Slater-Koster files
- **INPUT_files/** – Example DFTB+ input files
- **AgAu19/** – XYZ files for the octahedral (Oct) silver and gold (19-atom) nanoclusters
- **AgAu20alloys/** – XYZ files for the tetrahedra (Td) silver and gold (19-atom) nanoclusters and AgAu nanoalloys
- **AgAu38alloys/** – XYZ files for the truncated octahedron (TOh) silver and gold (38-atom) nanoclusters and AgAu nanoalloys
- **AgAu55alloys/** – XYZ files for the icosahedra (Ih) silver and gold (55-atom) nanoclusters and AgAu nanoalloys

## Supporting Files Description

The GS and ES Slater-Koster parameter files, containing the final parameters for monometallic and bimetallic clusters, are included in the `ESI_files.rar` folder.

### Ground State Slater-Koster Files
The `GSSK` folder contains the Slater-Koster parameter files for ground state calculations:

- `Ag-Ag-GS-SK.skf`
- `Au-Au-GS-SK.skf`
- `Ag-Au-GS-SK.skf`
- `Au-Ag-GS-SK.skf`

### Excited State Slater-Koster Files
The `ESSK` folder contains the Slater-Koster parameter files for excited state calculations:

- `Ag-Ag-ES-SK.skf`
- `Au-Au-ES-SK.skf`
- `Ag-Au-ES-SK.skf`
- `Au-Ag-ES-SK.skf`

### Example Input Files
Example input files for running ground state and excited state calculations are included in the `INPUT_files` folder.

---


## 📖 Citation
If you use these files in your research, please cite:

**Kumawat and Schatz, Efficient Modeling of Structural, Electronic, and Optical Properties of Silver and Gold Metal Nanoclusters and Alloys Using Optimized SCC-DFTB Parameters, *Journal of Physical Chemistry C*, 2025**  
[![DOI](https://zenodo.org/badge/DOI/000.svg)](https://doi.org/000)

### BibTeX:
```bibtex
@article{kumawat2025dftb,
  author = {Kumawat, Rameshwar and Schatz, George},
  title = {Efficient Modeling of Structural, Electronic, and Optical Properties of Silver and Gold Metal Nanoclusters and Alloys Using Optimized SCC-DFTB Parameters},
  journal = {Journal of Physical Chemistry C},
  year = {2025},
  volume = {xx},
  number = {x},
  pages = {x-x},
  doi = {000}
}
