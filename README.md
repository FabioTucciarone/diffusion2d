# diffusion2d

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Description

This code solves the diffusion equation over a two dimensional square domain which is at a certain temperature, and a circular disc at its center which is at a higher temperature. The diffusion equation is solved using the finite-difference method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.

## Installing the package

```sh
pip install -i https://test.pypi.org/simple/ tucciafo_diffusion --extra-index-url https://pypi.org/simple
```

## Running this package

In a script

```python
from tucciafo_diffusion2d import diffusion2d as diff

diff.solve()
```

From the console

```python
solve-diffusion2d
```

## Citing

[Chapter 7 "Learning Scientific Programming with Python"](https://scipython.com/books/book2/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/)
