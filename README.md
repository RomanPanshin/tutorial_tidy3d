# tutorial_tidy3d

Hands-on tutorials for [tidy3d](https://www.flexcompute.com/tidy3d/), Flexcompute's cloud-based electromagnetic and semiconductor device simulation package. Each tutorial is a self-contained Jupyter notebook, with a compiled PDF version alongside it.

## Tutorials

| # | Notebook | PDF | What it covers |
|---|----------|-----|-----------------|
| 1 | [`tidy3d_101.ipynb`](tidy3d_101.ipynb) | [`tidy3d_101/tidy3d101.pdf`](tidy3d_101/tidy3d101.pdf) | Getting started: what tidy3d is, the FDTD method, account setup, and a first simulation (a silver nanosphere) from geometry through results. |
| 2 | [`charge_solver.ipynb`](charge_solver.ipynb) | [`charge_solver/charge_solver.pdf`](charge_solver/charge_solver.pdf) | tidy3d's Charge solver: building a silicon PN junction diode, running a voltage sweep, and reading the I-V curve, potential, and carrier concentration results. |
| 3 | [`agent_skills.ipynb`](agent_skills.ipynb) | [`agent_skills/agent_skills.pdf`](agent_skills/agent_skills.pdf) | Using tidy3d's official agent integration, FlexAgent MCP, from Claude Code and Codex: installing the CLIs, registering the MCP server, and real terminal examples. |

Start with tutorial 1 if you're new to tidy3d.

## Requirements

- Python 3.9+
- A free [tidy3d account](https://tidy3d.simulation.cloud/signup) and API key (covered in `tidy3d_101.ipynb`)
- `pip install tidy3d`

## Repository structure

```
tutorial_tidy3d/
├── tidy3d_101.ipynb          # Tutorial 1 notebook
├── tidy3d_101/                # Tutorial 1: compiled PDF, LaTeX source, figures
├── charge_solver.ipynb       # Tutorial 2 notebook
├── charge_solver/             # Tutorial 2: compiled PDF, LaTeX source, figures
├── agent_skills.ipynb        # Tutorial 3 notebook
├── agent_skills/               # Tutorial 3: compiled PDF, LaTeX source
├── data/                      # Cached simulation results used by charge_solver.ipynb
└── images/                    # Screenshots used in tutorial 1
```
