# minipackage
A bare minimum Python package for collection of functions you can install from GitHub


## Basic Install
```
pip install git+https://github.com/scottyhq/minipackage.git@main
```
NOTE: if you need a fresh virtual environment: `conda create -n minitest python=3.10`

## Use
```python
import minipackage
minipackage.myfunction()
# 'hello'
```

## Other install options
1. Development ("Editable") install
```
git clone https://github.com/scottyhq/minipackage.git
cd minipackage
pip install --editable ./
```

2. A specific version (github tag)
```
pip install git+https://github.com/scottyhq/minipackage.git@v0.0.1
```
