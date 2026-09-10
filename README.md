# ml-ci-demo

A minimal ML project used to demonstrate Continuous Integration with GitHub Actions.

## Project structure
- `src/preprocess.py` — min-max normalization utility
- `src/train.py` — trains and evaluates a simple model on the Iris dataset
- `tests/` — unit tests and model quality checks

## Setup
\`\`\`
pip install -r requirements.txt
\`\`\`

## Run tests
\`\`\`
pytest -v
\`\`\`
