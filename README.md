# Second-Order Differential Machine Learning

For detailed background information, consider looking into:

https://neilkichler.github.io/master-thesis/Thesis.pdf

## Notebooks
The notebooks contain the majority of the code right now and accumulate the ideas that are needed for the proposed methods. The package currently implements the core
functions needed for Sobolev Training / Differential Machine Learning.

## Installation
Clone the repo and execute the following inside the root folder.

```bash
python -m pip install -e .
```

> Requires Python 3.9+, [JAX](https://github.com/google/jax) 0.4.16+ and [Equinox](https://github.com/patrick-kidger/equinox) 0.10.5+.

## Development
We use [Hatch](https://hatch.pypa.io/) as the project manager. The usual commands apply.

#### Show all available scripts
```bash
hatch env show
```
#### Run case study
```bash
hatch -e example run python examples/bachelier/bachelier.py
```
#### Run Tests
```bash
hatch run test:test
```
#### Build project wheel
```bash
hatch build
```
#### Lint project
```bash
hatch run lint:fmt
```


