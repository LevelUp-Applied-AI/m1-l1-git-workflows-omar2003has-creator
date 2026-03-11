## Testing Requirements
All changes must pass `python test_environment.py` before committing.

## Secrets Policy
Never commit `.env`, `*.key`, or any file containing credentials.

## Scope Boundaries
Agents may edit files in `src/` and `notebooks/`. Do not modify `requirements.txt` or `setup.sh` without manual human review.

## Reproducibility Standard
All AI-assisted changes must run locally and produce expected output before they are committed.