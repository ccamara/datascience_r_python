# R and Python comparison

This site is a proof of concept that aims to become a reference for people wanting to perform common tasks in data science using R or Python.

Site goals:

* Learn how specific tasks are done as compared to their programming knowledge
* Facilitate a transition from R to Python or from Python to R
* Become a reference material

## About the author(s)

So far this is a work by [Carlos Cámara](https://carloscamara.es/en), Senior Research Software Engineer at the University of Warwick's [Centre for Interidisciplinary Methodologies](https://warwick.ac.uk/fac/cross_fac/cim/), but it's open to collaboration.

## Project setup

This project uses quarto, R, Python, and virtual environments (see below) to handle python dependencies

### Virtual environments

Virtual environments are managed by conda, which means that you should have [Anaconda distribution](https://www.anaconda.com/) installed (Read [installing instructions on their website](https://www.anaconda.com/distribution/))

Activate virtual environment

```bash
conda activate datascience_r_python
```

Deactivate virtual environment:

```bash
conda deactivate
```

Update virtual environment from `environment.yml`:

```bash
conda env update -f environment.yml
```

Recreate virtual environment from `environment.yml`:

```bash
conda env create -f environment.yml
```
