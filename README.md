[![License](https://img.shields.io/badge/license-CC%20BY%204.0-informational)](./LICENSE)
![GitHub release](https://img.shields.io/github/v/release/aleph-fbk/The-Hitchhiker-s-Guide-to-Applied-Cryptography)
![GitHub release](https://img.shields.io/github/tag/aleph-fbk/The-Hitchhiker-s-Guide-to-Applied-Cryptography.svg?label=latest%20tag)

# The Hitchhiker's Guide to Applied Cryptography

This repository contains *The Hitchhiker's Guide to Applied Cryptography*, a handbook on the subject of applied cryptography written by the Applied Cryptography (**ALEPH**) research unit of the **Center for Cybersecurity** at **Fondazione Bruno Kessler**.

The main purpose of the handbook – available as a PDF (see below) – is to provide a **guided overview of relevant and current concepts in applied cryptography**. Each topic is accompanied by a brief explanation and, where appropriate, pointers to additional resources for deeper study. In other words, the handbook is a **starting point**, curated based on what we consider essential knowledge in this context, without claiming to be exhaustive or fully comprehensive.

> [!NOTE]
> 📄 [Download here the PDF (v0.1.0)](https://github.com/aleph-fbk/The-Hitchhiker-s-Guide-to-Applied-Cryptography/releases/download/0.1.0/the_hitchhiker_s_guide_to_applied_cryptography_v0.1.0.pdf)

## Table of Contents
- [How This Handbook is Structured](#how-this-handbook-is-structured)
- [What This Handbook Is Not](#what-this-handbook-is-not)
- [Intended Audience](#intended-audience)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [Citations](#citations)
- [Attribution and Disclaimer](#attribution-and-disclaimer)
- [Build it Locally](#build-it-locally)
- [License](#license)

---

## How This Handbook is Structured

The handbook is **structured as a series of self-contained notes**. 
Each note can be read independently, though references to related notes (denoted with `§`) or more detailed sources are included where useful.
While a top-down reading of the handbook is possible, readers can **read any one single note** based on their interests or needs

> [!IMPORTANT]  
> References to cryptographic services, libraries, or hardware **do not constitute endorsement**, unless explicitly stated.

---

## What This Handbook Is Not

The handbook is **not** a textbook, an encyclopedia, or a dictionary. Similarly, the handbook is by no means a horizontally complete or vertically exhaustive treatment of all facets of (especially theoretical) cryptography. 
In particular, to maintain brevity and focus, **the handbook intentionally minimizes**:

- mathematical details;
- formal proofs;
- descriptions of the inner functioning of cryptographic algorithms.

Instead, the emphasis is on practical understanding, conceptual clarity, and pointers to authoritative sources for readers who wish to explore further (see the `§ Further Resources` appendix).

---

## Intended Audience

The handbook is primarily aimed at readers who:

- seek a **practical understanding** of cryptography without delving (too much) into its theoretical foundations;
- need a **reference companion** to standard cryptographic literature;
- want a high-level overview of various **cryptographic components and their relationships**.

While prior familiarity with cryptography is helpful, the handbook is designed to remain accessible to readers with a general background in computer science or cybersecurity.

---

## Contributing

This is a living document, and ****contributions are welcome****.

Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on how to contribute corrections, suggestions, or new notes to the handbook.

---

## Changelog

For a detailed history of changes, see [CHANGELOG.md](./CHANGELOG.md).

---

## Citations

For citation information, please refer to [CITATION.cff](./CITATION.cff) (see the "Cite this repository" option under the description of this repository).

---

## Attribution and Disclaimer

Despite every effort to provide accurate attribution, some material has been compiled over many years. If any content lacks proper credit, please notify us and we will correct it promptly.

---

## Build it Locally

To build the PDF locally from the LaTeX source, run `pdflatex the_hitchhiker_s_guide_to_applied_cryptography.tex` (or use your preferred LaTeX editor/IDE) within the [the_hitchhiker_s_guide_to_applied_cryptography](./the_hitchhiker_s_guide_to_applied_cryptography) directory of the repository.

---

## License

This work is licensed under a Creative Commons Attribution 4.0 International License. You can view the license at [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

---

<div align="center">

  <img src="https://aleph.fbk.eu/assets/images/institutional/ALEPH_regular.png" alt="ALEPH logo" width="200" style="margin-right: 100px;">
  &nbsp;&nbsp;&nbsp;
  <img src="https://aleph.fbk.eu/assets/images/institutional/CS_regular.png" alt="CS Logo" width="200">

  <br>
  <br>

  [**Applied Cryptography**](https://aleph.fbk.eu/)<br>
  [**Center for Cybersecurity**](https://cs.fbk.eu/)<br>
  [**Fondazione Bruno Kessler**](https://www.fbk.eu/)<br>
  Via Sommarive, 18<br>
  38123 Povo, Trento, Italy
</div>






