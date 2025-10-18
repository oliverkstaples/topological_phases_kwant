This project studies a lattice realization of the Z2 topological insulator using the BHZ model.

Kwant does not run natively on Apple Silicon. To use Kwant on an M1/M2 Mac, open a Rosetta (x86) shell and create a Conda environment with Python 3.9. Example:

```bash
arch -x86_64 zsh
conda create -n kwant-env python=3.9
conda activate kwant-env
python -c "import kwant, platform; print(kwant.__version__, platform.machine())"
# Example output: 1.5.0 x86_64
```
