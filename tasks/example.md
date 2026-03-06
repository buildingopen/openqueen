# Task: example-task-name

## Project
path: ~/my-project              # required. ~ expanded to $HOME
worker: claude                  # claude | codex (default: claude)
new_project: false              # true = Claude creates folder + git init + README
env_file: ~/my-project/.env.local  # optional. vars loaded into worker subprocess env

## Objective
Describe exactly what needs to be done. Be specific — vague objectives produce vague results.
Include file names, function names, error messages, or any concrete details you have.

## Context / Constraints
Anything Gemini and the worker should know:
- Relevant architecture decisions
- Things to avoid
- Dependencies or limitations

## Done When
- Specific verifiable criterion 1 (e.g. "src/auth.py exists")
- Specific verifiable criterion 2 (e.g. "pytest tests/ passes with 0 failures")
- Specific verifiable criterion 3 (e.g. "git log shows a new commit")
