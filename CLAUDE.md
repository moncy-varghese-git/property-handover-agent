# Project Instructions

## Commands
- Create virtual environment: `python3 -m venv .venv && source .venv/bin/activate`
- Install dependencies: `pip install -r requirements.txt`
- Run tests: `pytest`

## Project Rules
- Stack: Python 3.11+ with a virtual environment in `.venv`, pip with `requirements.txt`, FastAPI, Pydantic, and pytest. Inspect `requirements.txt` before adding dependencies or choosing framework-specific patterns.
- Style: keep code clear, modular, and consistent with the existing project structure. Prefer focused changes over broad refactors.
- Domain: build for reliable property handover workflows, including clear validation and useful error messages.
- Tests: always write or update tests for new behavior and bug fixes. Run the relevant tests before completing a change.
- Dependencies: prefer the standard library and existing dependencies; add a new package only when it materially simplifies the implementation.
- Documentation: update `README.md` when setup steps, commands, or user-visible behavior changes.
- Secrets: secrets live in `.env` (git-ignored). Never print, log, hard-code, or commit the API key. Load it with `python-dotenv`.

## Guidelines
- Keep changes focused.
- Add tests for new behavior.
