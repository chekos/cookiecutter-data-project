Data Project template
====================

This is a cookiecutter project template based on [Cookiecutter Reproducible Science](https://github.com/mkrapp/cookiecutter-reproducible-science) which is in turn based on [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science)'s philosophy: *A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.*

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
To start a new science project:

`cookiecutter gh:chekos/cc-data-project`

Project Structure
-----------------

```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
├── docs               <- Documentation, e.g., doxygen or scientific papers (not tracked by git)
├── notebooks          <- Jupyter/Rmarkdown notebooks
├── reports            <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
│   └── figures        <- Figures for the manuscript or reports
└── src                <- Source code for this project
    ├── __init__       <- Makes src a Python module
    ├── apps           <- scripts for apps (flask, streamlit)
    ├── data           <- scripts and programs to process data
    ├── external       <- Any external source code, e.g., pull other git projects, or external libraries
    ├── models         <- Source code for your own model
    ├── tools          <- Any helper scripts go here
    └── visualization  <- Scripts for visualisation of your results, e.g., matplotlib, ggplot2 related.
```

License
-------
This project is licensed under the terms of the [BSD License](/LICENSE)
