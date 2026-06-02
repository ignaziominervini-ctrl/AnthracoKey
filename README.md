AnthracoKey
![DOI](https://zenodo.org/badge/1257098007.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status: development](https://img.shields.io/badge/status-development-orange.svg)
A single-file, offline generator of empirical dichotomous keys for anthracology.
AnthracoKey is the downstream companion to
AnthracoForm. It is a self-contained
HTML application that loads charcoal-determination CSVs (as exported by
AnthracoForm), computes empirical IAWA feature profiles per taxon, and builds
region-specific dichotomous identification keys using a greedy algorithm. It
runs entirely in the browser with no installation and no internet connection
required.
⚠️ Development status
This is a development release (v0.9-beta).
AnthracoKey is functional and has been validated on synthetic data.
Empirical validation on real charcoal datasets is in progress (IAWA coding of
reference material is being finalised). It is published now to obtain a citable,
date-stamped DOI for reference in forthcoming work. A stable v1.0 release will
follow once empirical validation is complete.
Use with appropriate caution: keys generated from incomplete or unvalidated
reference profiles may not be reliable for routine identification.
Features
Loads AnthracoForm determination CSVs
Computes empirical IAWA anatomical feature profiles per taxon
Builds region- (assemblage-) specific dichotomous keys via a greedy
feature-selection algorithm
Interactive key navigation; works on any computer with no browser storage
needed
Plain-text key export, ready to paste into a paper or report
Fully offline, no dependencies, no internet connection required
Usage
Open `AnthracoKey.html` in a modern browser (Chrome recommended, for File System
Access API support). No server, no dependencies, no internet connection needed.
How to cite
If you use AnthracoKey in your research, please cite it as:
> Minervini, I. (2026). *AnthracoKey: Data-driven dichotomous key generator for
> anthracology* (v0.9-beta, development release). Zenodo.
> https://doi.org/10.5281/zenodo.20508972
Authors
Ignazio Minervini, CASEs Research Group (Culture, Archaeology and Socio-Ecological
Dynamics), Universitat Pompeu Fabra, Barcelona.
AI Acknowledgement
AnthracoKey was developed with the assistance of Claude (Anthropic), an AI
assistant used throughout the design, coding, and testing of the tool. The
authors acknowledge the role of AI-assisted development in this work, in the
spirit of transparency encouraged by the scientific community.
License
Released under the MIT License. See the LICENSE file for details.
See also
AnthracoForm — the upstream
determination and analysis tool whose CSV exports AnthracoKey consumes.
