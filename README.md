# eyong0.github.io

## Overview

The following repository hosts the artifacts for a Github personal website for Edmund Yong. The website contains information about the creator as well as various blog posts.

## Prerequisites

- Git (V2.55.0(5))
- Quarto (V1.10.18)
- uv (V0.12.5)
- Python (V3.14)
- R (V4.6.1)

## Installation Guide

1. Clone the repository into your desired directory using either of the following in bash based on your circumstances:
    - User has valid SSH keys for this repo: `git clone git@github.com:eyong0/eyong0.github.io.git`
    - Other Users: `git clone https://github.com/eyong0/eyong0.github.io.git`
2. Navigate into the project repository using `cd eyong0.github.io`
3. Run `uv sync` to install the necessary Python packages.
4. Run R using `R` in the currect directory to start an R instance and execute `renv::restore()` to install the necessary R packages.

## Quick-Start Guide

Run either of the following commands from the project repository based on your intent:

- `uv run quarto preview` to open a live preview of the website that changes as you update the source code.
- `uv run quarto render` to build the website.
    - Building the website places the rendered files into the `/docs` sub-directory.

## Source Data
Horst AM, Hill AP, Gorman KB (2020). palmerpenguins: Palmer Archipelago (Antarctica) penguin data. R package version 0.1.0. [https://allisonhorst.github.io/palmerpenguins/](https://allisonhorst.github.io/palmerpenguins/). doi: 10.5281/zenodo.3960218.
