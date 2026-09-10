# ml-ci-demo

A minimal ML project used to demonstrate Continuous Integration with GitHub Actions.

## Project structure
- `src/preprocess.py` — min-max normalization utility
- `src/train.py` — trains and evaluates a simple model on the Iris dataset
- `tests/` — unit tests and model quality checks
- `.github/workflows/ci.yml` — automatic testing on push in main , or pull request on main

## Setup
\`\`\`
pip install -r requirements.txt
\`\`\`

## Run tests
\`\`\`
pytest -v
\`\`\`
