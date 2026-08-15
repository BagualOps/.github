<p align="center">
  <img src="assets/bagualops-logo.png" alt="BagualOps" width="560">
</p>

<p align="center">
  <b>Open-source tools for operating and securing Linux server fleets.</b><br>
  Built at AI Horizon Labs, Universidade Federal do Pampa (UNIPAMPA).
</p>

---

## Tools

### [AdminForge](https://github.com/BagualOps/adminforge-sbseg2026)

Declarative privileged-identity management for Linux server fleets. The operator declares the
desired access state — accounts, SSH keys, groups and grants — previews the resulting changes,
and applies them over SSH. Every operation is appended to a local, hash-chained history, and
**nothing is installed on the managed hosts**: no agent, no resident service.

| | |
|---|---|
| Runtime | Python ≥ 3.11, standard library only — **zero third-party runtime dependencies** |
| License | AGPL-3.0-or-later |
| Published at | SBSeg 2026, Salão de Ferramentas (open-source track) |
| Artifact | [`adminforge-sbseg2026`](https://github.com/BagualOps/adminforge-sbseg2026) — one command per claim, offline unit tests, reference results |
| Demo | [Vídeo de demonstração](https://youtu.be/6rs2qtIuMvs) — installation and features |

Everything a reader needs is in the artifact's own README, including how to run the minimal
test and reproduce each claim in the paper.

## What this organization is for

BagualOps holds the tools we build for real infrastructure work: operable from a terminal,
auditable after the fact, and reproducible by someone who was not in the room. Each tool ships
with its own artifact repository — tests, experiments and the data behind every published
number — so that a claim can always be re-run rather than taken on faith.

*Bagual* is the untamed horse of the Pampa, which is where the mark comes from.

## People

- **Rui de Quadros Ribeiro** — [ORCID 0000-0003-0287-9007](https://orcid.org/0000-0003-0287-9007) — AI Horizon Labs / PPGES, UNIPAMPA; CPD, UFRGS
- **Cristhian Kapelinski** — [ORCID 0009-0005-5750-022X](https://orcid.org/0009-0005-5750-022X) — AI Horizon Labs, UNIPAMPA
- **Diego Kreutz** — [ORCID 0000-0003-0830-0238](https://orcid.org/0000-0003-0830-0238) — AI Horizon Labs, UNIPAMPA

## Citing

Each repository carries a `CITATION.cff` and a citation section at the end of its README.
Please cite the paper the tool was published in, not the repository URL alone.
