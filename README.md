# `molli 1.0`: Molecular Toolbox Library

(C) 2022 Alexander S. Shved and the Denmark laboratory

## Code Design

Molli is a tool for people in cheminformatics to quickly and efficiently upload molecules into Python. Then, the molecules can be adjusted for visualization.

This is the repository for the documentation of molli. To generate this documentation yourself, the following is required. 

## Installation of Molli

The documentation imports the molli code locally. Consequently, molli must already be installed to generate this documentation. 
```
git clone https://github.com/SEDenmarkLab/molli 
cd molli 
pip install -e
```

## Necessary Dependencies for Building Documentation

```
pip install sphinx
pip install sphinx-rtd-theme
pip install myst-parser
pip install nbsphinx
pip install ipykernel
```

## Building Documentation

# Linux

1. Navigate to the `molli-docs` folder and run the following command
```
make html
```
2. Once finished, run the following commands
```
cd build
cd html
open index.html
```
Note: This can also be run with other commands such as 

```
xdg-open index.html
firefox index.html
google-chrome index.html
```

## Citation 
