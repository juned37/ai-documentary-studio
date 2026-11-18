# AI Documentary Studio

A clean, free-first foundation for generating illustrated documentary videos from a topic. This is a new implementation and does not depend on or modify `reel-maker`.

## Milestone 0: Foundation

Included: validated documentary brief format, deterministic scene planner, CLI, unit tests, and GitHub Actions CI.

Not included yet: AI research/script providers, illustration generation, text-to-speech, animation, or final MP4 rendering. These will be separate tested milestones.

## Requirements
- Python 3.11+
- No runtime third-party dependencies

## Setup
```bash
python -m venv .venv
# Linux/macOS: source .venv/bin/activate
# Windows PowerShell: .venv\Scripts\Activate.ps1
python -m pip install -e ".[dev]"
