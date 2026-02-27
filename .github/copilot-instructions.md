# Copilot Instructions for hedonometer-project

## Project Overview
This project demonstrates a step-by-step analysis using the labMT 1.0 dataset, following the structure and tasks of Seminars 3 & 4. The main script (`src/hedonometer_labmt_demo.py`) is written in a notebook-like style for clarity and reproducibility.

## Folder Structure
- `src/` — Python scripts (main: `hedonometer_labmt_demo.py`)
- `data/raw/` — Input data (read-only; main file: `Data_Set.txt`)
- `figures/` — Output PNG plots
- `tables/` — Output CSV summary tables
- `docs/` — Course documents (PDFs)

## Developer Workflow
1. **Environment Setup**
   - Create a virtual environment: `python3 -m venv .venv && source .venv/bin/activate`
   - Install dependencies: `python3 -m pip install -r requirements.txt`
2. **Run Analysis**
   - Execute: `python3 src/hedonometer_labmt_demo.py`
   - Outputs are saved to `figures/` and `tables/`

## Data Handling
- Input data is tab-delimited, with metadata in the first 3 lines and a header row.
- Treat files in `data/raw/` as read-only.

## Coding Patterns
- The main script is sequential, with minimal function abstraction (helpers only).
- Use pandas, numpy, and matplotlib for data processing and visualization.
- Output files are written directly to `figures/` and `tables/`.

## Conventions
- Follow the provided folder structure for all scripts and outputs.
- Do not modify input data files.
- Embed generated figures in the README for reporting.

## Integration Points
- No external APIs or services; all dependencies are listed in `requirements.txt`.
- Course documents in `docs/` provide assignment context and requirements.

## Example Commands
- Setup: `python3 -m venv .venv && source .venv/bin/activate && python3 -m pip install -r requirements.txt`
- Run: `python3 src/hedonometer_labmt_demo.py`

## References
- See `README.md` for assignment details and workflow.
- See `src/hedonometer_labmt_demo.py` for analysis steps and output conventions.
- See `docs/` for project requirements and quickstart.

---

**Feedback Requested:**
If any section is unclear or missing project-specific conventions, please specify so it can be improved for future AI agents.
