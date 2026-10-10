# BCI-2026

Offline decoding of motor intent from EEG. Right now we are in the decoding phase: reading the literature to learn which decoding methods work best for intent, and testing those methods in Python on offline data. Later we want to branch out into hardware: a BCI optimized for dry-electrode, offline decoding.

## Sections

| Section | What lives there |
|---|---|
| [literature/](literature/README.md) | One note per paper, plus a summary table |
| [experiments/](experiments/README.md) | One folder per experiment, plus an index table |
| [src/](src/README.md) | Reusable code promoted from experiments |
| [docs/decisions.md](docs/decisions.md) | Short log of "we chose X because Y" |

## Status

- [ ] Literature review started
- [ ] Baseline experiment (exp001) done
- [ ] Methods compared under one evaluation protocol
- [ ] Hardware requirements drafted

## How we work

1. Read a paper, then add a note in `literature/papers/` using `literature/_TEMPLATE.md`.
2. Test the method: copy `experiments/_TEMPLATE/` to a new numbered folder.
3. Log the result in the experiments index and link it back to the paper.
4. Record big choices in `docs/decisions.md`.

## Setup

(Add environment setup steps here, e.g. Python version and `pip install -r requirements.txt`.)
