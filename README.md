# NumPy practice notebook

[Open the notebook](numpy.ipynb) to see small examples of creating and inspecting arrays. The final cell compares a sequence defined by its step size with one defined by its number of points.

| Expression | What to look for |
| --- | --- |
| `np.zeros((3, 3))` | A three-by-three array initialized to zero |
| `np.eye(3)` | Ones on the main diagonal |
| `np.arange(0, 10, 2)` | Five even numbers from 0 through 8 |
| `np.linspace(0, 1, 5)` | Five points from 0 through 1, spaced 0.25 apart |

## Run locally

From this repository, in a Python environment:

```sh
python -m pip install numpy jupyterlab
python -m jupyterlab numpy.ipynb
```

In JupyterLab, select **Run → Run All Cells**. The random sample in the last cell uses a fixed seed so it can be reproduced in the same environment.
