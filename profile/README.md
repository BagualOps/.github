<p align="center">
  <img src="assets/bagualops-logo.png" alt="BagualOps" width="560">
</p>

<p align="center">
  <b>Open-source tools for managing Linux server fleets.</b><br>
  Built at AI Horizon Labs, Universidade Federal do Pampa (UNIPAMPA), Alegrete, Brazil.
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

All three of us are at AI Horizon Labs, UNIPAMPA.

- **Rui de Quadros Ribeiro**, also at UFRGS. [ORCID 0000-0003-0287-9007](https://orcid.org/0000-0003-0287-9007)
- **Cristhian Kapelinski**. [ORCID 0009-0005-5750-022X](https://orcid.org/0009-0005-5750-022X)
- **Diego Kreutz**. [ORCID 0000-0003-0830-0238](https://orcid.org/0000-0003-0830-0238)

## Citing

Every repository here carries a `CITATION.cff` file and a citation section at the end of its
README. Cite the paper the tool was published in, rather than the repository URL alone.
