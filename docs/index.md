# LDPS Probe documentation

The Probe currently has no separate component document set. Repository purpose, build entry, and
verification limits are summarized in:

- [README.md](../README.md)
- [STATUS.md](../STATUS.md)

Cross-product hardware protocols and decisions belong to the
[LDPS-Hardware documentation](https://github.com/Light-Dance-Pro/LDPS-Hardware/blob/main/docs/index.md).

## Shared validation

Run `python3 -m unittest tests.test_docs_lint tests.test_repo_lint`,
`python3 tools/docs_lint.py`, and `python3 tools/repo_lint.py`. The read-only
[`repository-check`](../.github/workflows/repository-check.yml) workflow runs the same baseline
for pull requests and `main` pushes.
