# Demo Math Ops

Source code for demo_math_ops Python package that provides basic math operations.
https://pypi.org/project/demo-math-ops


## Create Wheel & Source Distribution files
1. Clone the repo.
```sh
$ git clone https://github.com/rahg0/python-math-ops-package.git
$ cd python-math-ops-package
```

2. Install the tools setuptools, wheel, and twine needed to build & upload package.
```sh
$ pip install setuptools wheel twine
```

3. Build the distribution files.
```sh
$ python setup.py sdist bdist_wheel
```

4. Source distribution (**.tar.gz**) and Wheel file (**.whl**) will be placed under **`dist/`** directory.


## Install the Package from Local Package Source
```sh
$ pip install .

$ pip list

$ pip show demo_math_ops
```

## Usage within a Python Code
```sh
from demo_math_ops import add, sub, mult, div
```

## Upload the Package to PyPi (Optional)
```sh
$ twine upload dist/*
```

## Install the Package from PyPi
```sh
$ pip install demo_math_ops

$ pip list

$ pip show demo_math_ops
```


