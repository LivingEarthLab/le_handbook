# Living Earth Handbook

[![Living Earth](https://livingearthhub.org/assets/img/logos/living-earth-logo.svg)](https://livingearthhub.org)

This repository contains the source of the **Living Earth Handbook**, which describes the [Living Earth](https://livingearthhub.org) system and its different usages. It is maintained by the [Living Earth Lab](https://www.unige.ch/envirospace/livingearth) at the University of Geneva.

📖 **Read the handbook online: [livingearthlab.github.io/le_handbook](https://livingearthlab.github.io/le_handbook/)**

## Overview of Living Earth

Living Earth is an open source system that provides capacity to capture consistent and scalable information on the states and dynamics of past and present landscapes, to inform planning for the future. It is built on digital infrastructure based on the [Open Data Cube](https://www.opendatacube.org/) and takes Earth Observation to users through a workflow of:

1. Earth Observation data
2. Environmental descriptors
3. Classification of land cover and habitats
4. Evidence-based change
5. Future landscapes
6. Exploration and delivery

Living Earth is currently applied in Switzerland, Wales, and Australia. See the [Living Earth Hub](https://livingearthhub.org) and its [Knowledge Hub](https://livingearthhub.org/knowledge-hub/) for more.

## What's in the handbook

The handbook is written as a [Quarto](https://quarto.org/) book. Main chapters include:

| Chapter | Source |
|---------|--------|
| Introduction | [index.qmd](index.qmd) |
| Installation | [installation.qmd](installation.qmd) |
| Quick start | [quickstart.qmd](quickstart.qmd) |
| Introduction to LCCS | [intro_lccs.qmd](intro_lccs.qmd) |
| Change | [change.qmd](change.qmd) |
| Acknowledgements | [acknowledgements.qmd](acknowledgements.qmd) |

Additional material lives in the following folders:

| Folder | Content |
|--------|---------|
| [documentation](documentation) | Reference documentation |
| [tutorials](tutorials) | Step-by-step tutorials |
| [workshops](workshops) | Workshop material |
| [images](images) | Figures and logos used in the book |

> 🔧 *Adjust descriptions to match the actual content of each folder.*

## Building the book locally

You need [Quarto](https://quarto.org/docs/get-started/) installed.

```bash
git clone https://github.com/LivingEarthLab/le_handbook.git
cd le_handbook

# Live preview in your browser
quarto preview

# Or render the full book
quarto render
```

The book is configured in [`_quarto.yml`](_quarto.yml) and published from this repository as a website on GitHub Pages.

## Citation

If you use this book in your work, please use this reference:

> Gregory Giuliani, Richard Lucas, Carole Planque, Sébastien Chognard (2026). *Living Earth Handbook*. University of Geneva (UNIGE), Switzerland. Online book available at [https://github.com/LivingEarthLab/le_handbook](https://github.com/LivingEarthLab/le_handbook). [DOI: 10.5281/zenodo.13381515](https://zenodo.org/doi/10.5281/zenodo.13381515).

```bibtex
@book{giuliani_livingearth_handbook,
  author    = {Giuliani, Gregory and Lucas, Richard and Planque, Carole and Chognard, Sébastien},
  title     = {Living Earth Handbook},
  year      = {2026},
  publisher = {University of Geneva (UNIGE)},
  doi       = {10.5281/zenodo.13381515},
  url       = {https://github.com/LivingEarthLab/le_handbook}
}
```

## Intellectual property rights

The text of this book is licensed as [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) by Creative Commons.

The code in this repository is released under the [European Union Public Licence v1.2 (EUPL-1.2)](LICENSE.txt).

## Contributor guidelines

Contributions are welcome and greatly appreciated! Please also read our [Code of Conduct](CODE_OF_CONDUCT.md). To contribute, please follow these guidelines:

**Reporting issues**
* Check that the issue has not already been reported on the [issue tracker](https://github.com/LivingEarthLab/le_handbook/issues).
* Submit a new issue on the [issue tracker](https://github.com/LivingEarthLab/le_handbook/issues).

**Development process**
* Fork the repository, make changes in your fork, and submit a pull request.
* Follow the existing writing style and structure.
* Make sure the book renders without errors (`quarto render`) before submitting.
* Document any changes in your pull request description.

**Where to get help**
* Maintainer: [Gregory Giuliani](https://www.unige.ch/envirospace/people/giuliani)

## Acknowledgements

See the [acknowledgements](https://livingearthlab.github.io/le_handbook/acknowledgements.html) page of the handbook.
