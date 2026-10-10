# Experiments

One folder per experiment, numbered and never deleted. If an experiment fails, record why in its README.

## Starting a new experiment

1. Copy `_TEMPLATE/` to `expNNN-short-name/` (example: `exp002-csp-lda`).
2. Fill in its README before running anything (question, setup, how to run).
3. Add a row to the index below and link the paper(s) it tests.

## Rules

- Never commit datasets. List download steps in the experiment README.
- Fix random seeds and save the config used for every run.
- State the evaluation protocol: within-subject CV or leave-one-subject-out.
- Keep code inside the experiment folder until a second experiment needs it, then move it to `src/`.

## Index

| ID | Date | Method | Dataset | Acc | Status | Paper |
|---|---|---|---|---|---|---|
| [exp001](exp001-bandpower-svm/README.md) | | Band power + SVM | | | planned | |
