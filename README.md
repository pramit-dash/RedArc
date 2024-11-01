# RedArc

**RedArc** is a tool for tracking the trajectory of a cricket ball in video footage, specifically targeting red balls in 
well-lit conditions. This project is designed as a Proof of Concept (PoC) for detecting and tracing the path of a ball 
bowled on a cricket pitch using a combination of computer vision and Python libraries.

## Features

- Detect and track red cricket balls in video footage
- Save trajectory data in JSON format
- Overlay trajectory path on the video footage

## Project Structure

- `src/redarc/`: Contains the core code for tracking and detecting the cricket ball
- `tests/`: Test cases for core modules
- `docs/`: Project documentation including architecture decisions and development roadmap
```
RedArc/
├── src/
│   └── redarc/              # Main package directory       
├── tests/                   # Test directory
├── .gitignore
├── README.md
├── pyproject.toml
├── poetry.lock              # Poetry lock file
└── docs/
    ├── ADR/                 # Architecture Decision Records
    │   └── ADR-001-Project-Structure.md
    ├── CONTRIBUTING.md      # Etiquette for Contributions
    ├── DEVELOPMENT_PLAN.md  # Project development roadmap
    └── DESIGN_OVERVIEW.md   # Overview of system design
```

## Getting Started

### Prerequisites

- Python 3.11 or above
- Poetry for dependency management

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/pramit-dash/redarc.git
    cd redarc
    ```
2. Set up python env for the project
   ```bash
   poetry env use 3.11
   ```

3. Install dependencies with Poetry:
    ```bash
    poetry install
    ```

4. Run tests to confirm setup:
    ```bash
    poetry run pytest
    ```

## Usage

To start the tracker on a sample video file:
```bash
poetry run python src/redarc/tracker.py --video path/to/video.mp4
```