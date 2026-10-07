# AI-Work

Repository for empirical research code, experiments, and reproducible results.

## Suggested structure

- `src/` — research code and scripts
- `notebooks/` — exploratory analysis notebooks
- `data/` — local datasets (raw data should not be committed)
- `results/` — generated outputs (figures, tables, checkpoints)

## Getting started

```bash
git clone <your-repo-url>
cd AI-Work
```

Add your code in `src/`, keep experiments in `notebooks/`, and commit changes regularly to track versions.

## Version management workflow

```bash
git checkout -b feature/<short-description>
# make changes
git add .
git commit -m "Describe your research change"
git push -u origin feature/<short-description>
```

Use pull requests to review and merge changes to your main branch.
