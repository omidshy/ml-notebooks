`ml-notebooks` is a collection of machine learning-related Jupyter notebooks for educational purposes.

The simplest way to run the notebooks locally is to clone this repository and use `uv` to setup a
virtual Python environment with all the required dependencies.

Clone this repository using:

```bash
git clone https://github.com/omidshy/ml-notebooks.git
```

this should create a direcory named `ml-notebooks`.

For installing `uv` check [`uv` installation](https://docs.astral.sh/uv/getting-started/installation/).
After installing `uv` run the following command in your `ml-notebook` directory to create a virtual env
and install required packages to run the notebooks:

```bash
uv sync
```

To use the notebooks, run the following command in your `ml-notebook` directory:

```bash
uv run jupyter lab
```
