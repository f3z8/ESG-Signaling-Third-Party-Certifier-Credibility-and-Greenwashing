# ESG Signaling, Certifier Credibility, and Greenwashing

This repository contains the Python simulation code and replication materials for the paper:

**How Firm ESG Signaling and Third-Party Certifier Credibility Shape Investment Decisions in Markets Prone to Greenwashing**

## Overview

This project uses an agent-based evolutionary simulation to study how third-party certifier credibility affects investment decisions in an ESG market where firms can either make genuine sustainability investments or greenwash.

The model compares two certification environments:

- High-credibility certification: `a = 0.90`
- Low-credibility certification: `a = 0.60`

The simulation tracks greenwashing persistence, greenwashing investment success, investor decision success, certifier reputation, investor trust, and ESG quality diagnostics over time.

## Repository Contents

- `esg_certifier_simulation.py` — main Python simulation script
- `requirements.txt` — Python package requirements
- `manuscript.pdf` — paper draft
- `LICENSE` — repository license

## Reproducibility

The manuscript results are generated using `seed = 42` for both certification scenarios. Running the simulation script recreates the main outputs used in the paper.

## Requirements

The simulation uses the following Python packages:

- `numpy`
- `pandas`
- `matplotlib`
- `scipy`

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Running the Simulation

After installing the required packages, run:

```bash
python esg_certifier_simulation.py
```

The script saves simulation CSV files in `outputs/` and figures in `figures/`.

## Author

Siddhant Rana  
Independent Researcher
