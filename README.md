# w2w
Word to World models

## Overview

This repository is a place to run experiments and prototype tools for the creation of world models from natural language descriptions. We also run predictive simulations using these models.

## Approach

We use independent Python notebooks for experimentation and prototyping.

## Dependencies

This project uses [uv](https://github.com/astral-sh/uv) for dependency management. The main dependencies include:

- **pyro-ppl**: Probabilistic programming framework for building world models
- **transformers**: HuggingFace library for language models
- **datasets**: HuggingFace datasets library
- **jupyter**: Jupyter notebook environment for interactive development
- **torch**: PyTorch for neural network components

## Setup

1. Install uv (if not already installed):
   ```bash
   pip install uv
   ```

2. Install project dependencies:
   ```bash
   uv sync
   ```

3. Run Jupyter notebooks:
   ```bash
   uv run jupyter notebook
   ```

## Project Structure

```
w2w/
├── notebooks/          # Jupyter notebooks for experiments
├── pyproject.toml      # Project configuration and dependencies
└── README.md           # This file
```

## Getting Started

Check out the notebooks in the `notebooks/` directory:
- `01_getting_started.ipynb`: Introduction and environment verification

## Development

To add new dependencies:
```bash
uv add <package-name>
```

To run a specific notebook:
```bash
uv run jupyter notebook notebooks/01_getting_started.ipynb
```
