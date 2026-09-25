# Linear Algebra → Tensors — Python Lab

A Jupyter notebook that goes with a linear algebra tutoring course. There is one section per lesson: Σ/index notation, dot product, norms and projection, matrices as transformations, determinant, transpose, Einstein notation (`np.einsum`) and trace. Eigenvectors and tensors are planned.

Each lesson has the same parts: a recap, worked steps in code, a "Code it yourself" task, and exercises you can check yourself.

## Setup

You need [uv](https://docs.astral.sh/uv/). uv installs Python 3.14 for you if you don't have it.

```bash
uv sync                 # create .venv and install the dependencies
uv run jupyter lab      # open Linear_Algebra_Python_Lab.ipynb
```

If you use VS Code, run `uv sync` and pick `.venv` as the notebook kernel.
