# Contributing to BookMyHall

Thanks for your interest in contributing! This document explains how to get started contributing code, docs, or other improvements.

## Getting started
1. Fork the repository and clone your fork.
2. Create a feature branch: git checkout -b feat/short-description
3. Make small, focused changes and add tests where appropriate.
4. Push your branch and open a Pull Request against the main branch.

## Branching & Commits
- Branch names: feat/..., fix/..., docs/..., chore/...
- Commit messages: Use imperative present tense (e.g., "Add login endpoint")
- Keep PRs focused and include a clear description of what changed and why.

## Code style
- Frontend: follow ESLint and Prettier configs (setup in repo)
- Backend: follow Black and isort for Python; use type hints

## Running locally
- Frontend (Next.js):
  - cd frontend/client
  - npm install
  - npm run dev
- Backend (FastAPI):
  - cd backend/api
  - python -m venv .venv
  - source .venv/bin/activate
  - pip install -r requirements.txt
  - uvicorn app.main:app --reload

## Tests
- Frontend: npm test
- Backend: pytest

## Issues & PRs
- Create issues with a descriptive title and steps to reproduce (for bugs) or a clear proposal (for features)
- Link related issues in your PR
- Tag maintainers using the @ handle if you need help

Thanks — we appreciate your contributions!
