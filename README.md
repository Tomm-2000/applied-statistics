# Applied Probability & Statistics

Two runnable notebooks connect probability distributions and parameter estimation with small simulations. The exercises use simulated or explicitly defined examples and require no external dataset.

| Notebook | Focus |
| --- | --- |
| [Applied statistics](applied-statistics.ipynb) | Distribution calculations, sampling distributions, central limit theorem demonstrations, and estimation. |
| [Statistics explained](statistics-explained.ipynb) | Annotated versions of the exercises, including binomial and exponential examples and Gaussian maximum-likelihood estimation. |

## Run locally

From the repository root, use a fresh Python 3.11 environment.

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

Open either notebook and run the cells in order. Compare theoretical quantities with the simulated histograms and printed estimates. Individual draws can vary between runs, so compare the overall pattern as well as single numerical outputs.
