<p align="center">
  <img src="assets/bagualops-logo.png" alt="BagualOps" width="560">
</p>

<p align="center">
  <b>Open-source tools for managing Linux server fleets.</b><br>
  Built at <a href="https://ai-horizon-labs.github.io/">AI Horizon Labs</a>, in Alegrete, Rio Grande do Sul, Brazil.
</p>

## Tools

### [AdminForge](https://github.com/BagualOps/adminforge-sbseg2026)

AdminForge manages accounts, SSH keys, groups and access permissions across a fleet of Linux
servers from a single operator machine. The operator writes down the access state the fleet
should have, previews the changes that would follow from it, and applies them over SSH. Every
operation is appended to a local history in which each entry carries a hash of the entry before
it, so a later edit to the record is detectable. Nothing is installed on the managed hosts: no
agent, no resident service, only SSH.

| | |
|---|---|
| Runtime | Python 3.11 or newer, standard library only. There are no third-party packages to install, and none that can later break the tool. |
| License | AGPL-3.0-or-later |
| Published at | SBSeg 2026, Salão de Ferramentas, the open-source track of the Brazilian Symposium on Information and Computer System Security |
| Artifact | [`adminforge-sbseg2026`](https://github.com/BagualOps/adminforge-sbseg2026), with one command per claim in the paper, offline unit tests, and the reference results |
| Demonstration | [Video](https://youtu.be/6rs2qtIuMvs), in Portuguese, covering installation and use |

The artifact's own README is the only file a reader needs: it explains how to run the minimal
test and how to reproduce each claim.

## What this organization is for

BagualOps holds the tools we build for server administration work. Each tool comes with an
artifact repository that carries its tests, its experiments, and the data behind every number
published about it, so a reader can re-run a claim instead of taking it on trust.

A *bagual* is an untamed horse of the Pampa, the grasslands of southern Brazil. That is where
the mark comes from.

## People

We work at [AI Horizon Labs](https://ai-horizon-labs.github.io/), a research group on
artificial intelligence and software engineering at the Universidade Federal do Pampa
(UNIPAMPA), on the Alegrete campus in Rio Grande do Sul, Brazil. The group is tied to the
university's graduate program in software engineering (Programa de Pós-Graduação em Engenharia
de Software, PPGES).

- **Rui de Quadros Ribeiro**, AI Horizon Labs and PPGES at UNIPAMPA, and the data processing
  center (Centro de Processamento de Dados, CPD) of the Universidade Federal do Rio Grande do
  Sul (UFRGS).
  [ORCID](https://orcid.org/0000-0003-0287-9007) ·
  [Lattes](http://lattes.cnpq.br/3586977972572902) ·
  [GitHub](https://github.com/ruiribeirotk) ·
  [LinkedIn](https://www.linkedin.com/in/ruiribeirotk/)
- **Cristhian Kapelinski**, AI Horizon Labs at UNIPAMPA.
  [ORCID](https://orcid.org/0009-0005-5750-022X) ·
  [GitHub](https://github.com/CristhianKapelinski)
- **Diego Kreutz**, AI Horizon Labs and PPGES at UNIPAMPA.
  [ORCID](https://orcid.org/0000-0003-0830-0238) ·
  [Lattes](http://lattes.cnpq.br/2781747995973774) ·
  [Google Scholar](https://scholar.google.com/citations?user=JcL8biEAAAAJ) ·
  [GitHub](https://github.com/diegokreutz) ·
  [LinkedIn](https://www.linkedin.com/in/diegokreutz/)

Lattes is the Brazilian national registry of researcher CVs, maintained by CNPq, the federal
research council.

## Citing

Every repository here carries a `CITATION.cff` file and a citation section at the end of its
README. Cite the paper the tool was published in, rather than the repository URL alone.
