# groundtruth

Numerical and statistical methods, built from scratch.

## Aim

To understand methods by implementing them: every algorithm here is written
from first principles, tested, and documented. The library supports
[studies](https://github.com/Gomolemo-Sebothoma/studies), which apply these
methods to South African data.

## Roadmap

- [ ] `numerics`: bisection, regula falsi, Newton-Raphson, secant, fixed-point iteration
- [ ] `stats`: linear regression, logistic regression, survey-weighted estimators
- [ ] `data`: loaders for Stats SA / DataFirst datasets
- [ ] Convergence plots and error analysis for every method

## Principles

- **From scratch.** Existing libraries are checked first. A method is built here
  because a tool is missing, or as a deliberate learning exercise, and the
  README of that module says which.
- **Tested.** Each method has tests with known answers.
- **Documented.** Type hints, docstrings and a usage example for every function.

## Data

Datasets are not redistributed. Each loader links to the original source and
states its licence and citation requirements.

## Status

Early stage, under active development.

## Licence

MIT
