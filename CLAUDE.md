# Tron Legacy MPF: instructions for Claude

This repository is the MPF recreation of Stern Tron Legacy, built by a set of agents. The agents and the
knowledge base are game agnostic and live in Ashram56/Stern-SAM-Decryption (`../Stern-SAM-Decryption` when
cloned beside this repository, else on GitHub): read its `agents/README.md` (the master plan) first, then only
the agent file your task needs. The Tron game page below has Tron's status, open work and decisions. Update
the agent file (PR on Stern-SAM-Decryption) or this page in the same session when you learn something it
should say.

## This fork: the PuP Pack (kept below upstream's text, so a sync keeps both)

This is Tron-Legacy-MPF plus the PuP Pack: the agent is G, `agents/pup_pack.md` in Stern-SAM-Decryption (Jetson
cabinets: `agents/packaging.md`, section 5a). Tron's G status and open work: the game page, "G, PuP Pack"
(`docs/agents/README.md`, which arrives with the next upstream sync; until then read it on Tron-Legacy-MPF `main`).
How the pack is wired in: [docs/pup/README.md](docs/pup/README.md).

- **Feed back every game-agnostic learning** to Stern-SAM-Decryption in the same session, without asking: a PR
  (the owner has write access there), per its `CONTRIBUTING.md`. Tron facts go on the game page or in `docs/pup/`.
- Game fixes go to Tron-Legacy-MPF first and reach this fork by `python scripts/sync_upstream.py`; upstream files
  here get one-line hooks only. The fork's own files stay in its folders (marked *(PuP)* in the README's folder
  tree; add new folders there). Never move `scripts/gozen/`, `scripts/install/`, `pup_addons/`,
  `docs/upstream_issues/`: filed upstream issues and the one-line installers link to them.
- Colourisation work never comes here (private repository only).

@docs/agents/README.md
