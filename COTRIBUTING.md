# Contributing Guide

## Branch Strategy
- `main` = production branch
- Direct push to main is avoided
- All changes must go through Pull Requests

## Development Flow
1. Create an Issue (recommended for non-trivial changes)
2. Create a feature branch from main
```
feature/<issue-number>-<short-description>
```
3. Implement changes
4. Open a Pull Request to main
5. Ensure CI passes
6. Request approval from a repository maintainer
7. Merge to main

## Commit Message Convention

We loosely follow Conventional Commits.

Examples:
```
feat: add new news page
fix: correct typo in member profile
chore: add CI workflow
docs: update README
```

## CI Policy

Pull Requests trigger a Hugo build check via GitHub Actions.
CI must pass before requesting approval.

Workflow: `.github/workflows/ci.yml`

## Content Update Rules

### News

Add Markdown under:
`content/news/`

### Members

Edit files under:
`content/authors/`

### Publications

Update:
`content/publication/`

## Release Policy

Merging into main triggers automatic deployment.
