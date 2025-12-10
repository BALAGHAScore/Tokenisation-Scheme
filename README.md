[![BALAGHA Score](static/logo.png "Encyclopedia of Arabic Rhetoric.")](https://al-balagha.com)
# [Arabic Word Tokenisation Scheme (v0.1.0)](https://github.com/BALAGHAScore/Tokenisation-Scheme/tree/v0.1.0)
### Part of the [BALAGHA Score](https://balaghascore.com) Arabic Rhetoric Scoring System

A linguistically principled, rhetoric-oriented **morphological tokenisation framework** for tokenising Arabic words into constituent **meaning-bearing word units** for [rhetorical density](https://rhetorical-density.com) calculations and other digital humanities applications.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17877973.svg)](https://doi.org/10.5281/zenodo.17877973)


&nbsp;
## ℹ️ About
The **[Arabic Word Tokenisation Scheme](https://doi.org/10.5281/zenodo.17877973)** is a formal set of rules for consistently segmenting Arabic text into meaningful word units, optimised for the calculation of the **[BALAGHA Score](https://balaghascore.com)** — a quantitative metric of rhetorical density in both classical and contemporary Arabic texts.

Unlike general NLP tokenisers, this scheme defines token boundaries based on a **meaning-first philosophy** tailored to rhetorical analysis. It was originally developed in 2022 as part of the author’s [research](https://doi.org/10.48550/arXiv.2507.21106) into rhetorical density and has since been refined for broader computational, DH, and corpus-linguistic applications.

This repository serves as the **open, citable, version-controlled reference** of the Arabic Word Tokenisation Scheme.
The scheme is freely released under **CC BY 4.0** to support reproducible research in Arabic NLP, digital humanities, education, and rhetorical studies.

📄 Zenodo DOI: [https://doi.org/10.5281/zenodo.17877973](https://doi.org/10.5281/zenodo.17877973)


&nbsp;
### 🎯 Purpose
The Arabic Word Tokenisation Scheme provides:  

- A **stable, reproducible definition** of "word unit" for rhetorical density metrics.  

- A **principled approach** balancing linguistic structure with computational practicality.  

- A clear set of **syntactic, morphological, and orthographic rules** for segmenting Arabic words.  

- Representative **examples** for handling classical, modern, and social-media Arabic.  

- A **documented framework** that can be applied or extended to other DH and NLP tasks.  


&nbsp;
### 🧭 Tokenisation Philosophy
The overarching aim of the Arabic Word Tokenisation Scheme is to yield conceptually coherent, minimally sufficient word units by:  

- **Breaking compound words** into their smallest meaning-carrying units,  

- **Avoiding sub-atomic splitting** of verbs and historically fused forms,  

- **Merging redundant components** that express a single conceptual entity.  


&nbsp;
### 🔍 What the Scheme Covers
Full details are provided in the [PDF](Arabic_Word_Tokenisation_Scheme_v0.1.0.pdf), but the scheme includes rules for:  

#### Syntactic Segmentation
- Proclitics  
- Enclitic pronouns  
- Interrogative prefixes  
- Prepositions and particles  

#### Morphological Preservation
- Nisba forms remain whole
- Verbal and nominal stems are not decomposed
- Fused particles preserved as units
- No derivational segmentation

#### Orthographic Normalisation
- Removal of diacritics
- Collapsing elongated letters
- Removal of tatwīl
- Standard handling of digits, dates, currencies, percentages

#### Modern Digital Text Features Handling
- URLs
- Hashtags
- @mentions
- Emojis
- Abbreviations
- Arabic-script company names
- Multi-word names and iḍāfa structures

#### Worked Example
A fully annotated example paragraph is included in the PDF, demonstrating how the rules apply in realistic text.


&nbsp;
### 🔄 Versioning

The Arabic Word Tokenisation Scheme uses **Semantic Versioning (SemVer)**:
* [10 December 2025 - v0.1.0](https://github.com/BALAGHAScore/Tokenisation-Scheme/tree/v0.1.0)  
First public release of the tokenisation scheme on GitHub and Zenodo.
Includes complete documentation (PDF) and example workflows.


&nbsp;
### 📦 Repository Contents
```
/
├── README.md
├── LICENSE.txt
├── CITATION.cff
├── CHANGELOG.md
├── Arabic_Word_Tokenisation_Scheme_v0.1.0.pdf
└── static/
```

&nbsp;
### 📖 How to Cite
**APA:**
Marathe, M. (2025). BALAGHAScore.com Arabic Word Tokenisation Scheme v0.1.0 [Data set]. Zenodo. https://doi.org/10.5281/zenodo.17877973

**Chicago:**
Marathe, Mandar. 'BALAGHAScore.com Arabic Word Tokenisation Scheme v0.1.0'. Data set, Zenodo, 2025. https://doi.org/10.5281/zenodo.17877973

**BibTeX:**
```bibtex
@dataset{balaghascore2025,
  author = {{Mandar Marathe}},
  title = {BALAGHAScore.com Arabic Word Tokenisation Scheme v0.1.0},
  year = {2025},
  version = {0.1.0},
  url = {https://doi.org/10.5281/zenodo.17877973
}
```

&nbsp;<br>
---
## 📬 About the Author
**[Dr Mandar Marathe](https://marathe.org)** | [SOAS Profile](https://www.soas.ac.uk/about/mandar-marathe)  
PhD Researcher in Arabic Rhetoric | SOAS University of London  
[![Project Home](https://img.shields.io/badge/BALAGHA%20Score-Home-green)](https://balaghascore.com)  

### Related Projects
- 📚 [Encyclopedia of Arabic Rhetoric](https://al-balagha.com) - Reference source for Arabic rhetorical devices  
- 💯 [BALAGHA Score](https://balaghascore.com) - Arabic rhetorical density analysis  
- 📖 [Balagha Corpus](https://balagha-corpus.com) - Annotated texts for Arabic rhetorical analysis  
- 📡 [BalaghaBase.org](https://balaghabase.org) - Semantic knowledge graph for Arabic rhetoric  
- 🔬 [Rhetorical Density](https://rhetorical-density.com) - Methodology and discussion of rhetorical density as a quantitative metric  

### Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/mandar-marathe-uk/) [![ORCID](https://img.shields.io/badge/ORCID-Profile-green.svg)](https://orcid.org/0000-0002-6927-6836) [![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-blue)](https://scholar.google.com/citations?user=w-bT-iYAAAAJ)  
---
_Last updated: 10 December 2025._  