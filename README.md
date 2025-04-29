# SSP_Uganda
This repository stores the notebooks to run the SSP model on Uganda's mitigation scenarios.

## Get Started

Create a conda environment with Python 3.11 (you can use any name):

```bash
conda create -n sisepuede python=3.11
```

Activate the environment:

```bash
conda activate sisepuede
```

Install the working version of the sisepuede package:

```bash
pip install git+https://github.com/jcsyme/sisepuede.git@working_version
```

Install additional libraries (make sure to be inside ssp_uganda folder):

```bash
pip install -r requirements.txt
```

## Repository Structure

**ssp_uganda/**
- **LICENSE** — MIT License for the project.
- **README.md** — Project overview and instructions.
- **requirements.txt** — List of required Python packages.
- **.gitignore** — Specifies files and folders to ignore in Git.
- **ssp_modeling/** — Main directory containing simulation components:
  - **config_files/** — Configuration files for model parameters and setups.
  - **input_data/** — Raw or processed input data for simulations.
  - **misc/** — Miscellaneous supporting scripts or data.
  - **notebooks/** — Jupyter notebooks to run the simulation.
  - **scenario_mapping/** — Excel files that map different simulation scenarios.
  - **transformations/** — transformations and strategies files.