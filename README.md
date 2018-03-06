# Quadratic Equations Solver

This module need for decide quadratic equation.

# How to use

Function:

 ``` get_roots(a, b, c)``` - return a tuple of 2 elements:

1. ```root1``` и ```root2``` - *for discriminant > null*

1. ```root1``` и ```None``` - *for discriminant = null*

1. ```None``` и ```None``` - *for discriminant < null*

### Simple:
```python
from quadratic_equation import get_roots

root1, root2 = get_roots(1, 2, 3)
```
# Automatic check before commit

File named ```pre-commit``` move to folder ```.git/hooks/``` this project.

This is necessary to start the test automatically before committing. If the test without errors is successful. If the test fails, the commit is rejected.

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
