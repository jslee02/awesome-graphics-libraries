# Contribution Guidelines

## Suggesting a New Resource

Please use the GitHub issue form for new suggestions:

- Open `Suggest a Resource`
- Fill in the category, description, and repository fields as completely as you can
- Search existing issues and entries first to avoid duplicates

## Fixing an Existing Entry

This repository uses a data-first workflow:

- YAML files are the source of truth
- `README.md` is generated from YAML data

If you are opening a direct PR:

1. Edit the relevant YAML/source file, not `README.md`
2. Keep entries in the correct section and order
3. Run `python3 scripts/validate_entries.py`
4. Run `python3 scripts/generate_readme.py`
5. Commit the regenerated `README.md`
6. Sign off commits with `git commit --signoff`

## General Rules

- Keep descriptions short, factual, and easy to scan
- Use the appropriate category and subsection
- Check spelling and grammar
- Remove trailing whitespace

Thank you for the contribution.

