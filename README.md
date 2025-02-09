# quarto-simple-rdm-tutorial

## Overview
This repository contains the project sources and output files for the article:  
**"Veröffentlichung von Forschungsdaten: Ein Leitfaden mit Markdown für GitHub und Zenodo"** (german, web page and PDF document).  
DOI of the article: [![DOI](https://zenodo.org/badge/928431889.svg)](https://doi.org/10.5281/zenodo.14840823)

## Project Description

```
quarto-simple-rdm-tutorial/
├─ assets/
├─ docs/
├─ img/
├─ _quarto.yml
├─ .gitignore
├─ 01_Grundlagen.qmd
├─ 02_DMP.qmd
├─ 03_FAIR.qmd
├─ 04_SemVer.qmd
├─ 05_Fazit.qmd
├─ appendix.qmd
├─ CHANGELOG.md
├─ index.qmd
├─ LICENSE
├─ MAKEFILE
├─ README.md
├─ references.bib
├─ references.qmd
```

- `assets/`
  - Additional files for output generation.

- `docs/`
  - Output directory
  - Contains a web page and a PDF document as output

- `img/`
  - Contains image files used in the output

- `_quarto.yml_/`
  - Quarto project configuration file, contains metadata

- `.gitignore`
  - Used in a git repository to ignore local files and directories which are unnecessary to the project

- `.qmd` files
  - Content files written in Quarto markdown text format

- `CHANGELOG.md`
  - Documents changes between different vesions of the project

- `LICENSE`
  - License file

- `MAKEFILE`
  - Defines a set of tasks to be executed for output generation

- `README.md`
  - This readme document

- `references.bib`
  - Contains the list of references formatted using the [BibTeX](https://www.bibtex.org/de/) format


## How to Use
1. Clone this repository: `gh repo clone sgudenkauf/quarto-simple-rdm-tutorial`
2. Navigate through the folders for relevant files.
3. See `docs/` for the article as a self-contained web page and a PDF document.   
4. Refer to `_quarto.yml_` for detailed descriptions of the dataset and methodology.

## Citation
If you use this project, please cite:  
- **Project**: [![DOI](https://zenodo.org/badge/928431889.svg)](https://doi.org/10.5281/zenodo.14840823)
- **Paper**: None yet published

## License
This repository is licensed under the [MIT License](https://opensource.org/license/mit). See `LICENSE` file for details.

## Acknowledgments

This work was supported by the Lower Saxony Ministry for Science and Culture with funds from the governmental funding initiative zukunft.niedersachsen of the Volkswagen Foundation, project "Data-driven health ([DEAL](https://www.jade-hs.de/forschung/forschungsprofil/strategische-projekte/data-driven-health/))".
