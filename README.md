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
```py
from demo_math_ops import addition_module, subtraction_module, multiplication_module, division_module
```
OR
```py
from demo_math_ops import add, sub, mult, div
```

### Sample Python code
```py
from demo_math_ops import add, sub, mult, div

# Initialise some integer variables
value1 = 5
value2 = 3

print("Adding {0} and {1} gives {2}".format(value1, value2, add(value1, value2)))
print("Subtracting {0} from {1} results in {2}" .format(value1,value2, sub(value1,value2)))
print("Multiplying {0} by {1} equals {2}" .format(value1,value2, mult(value1,value2)))
print("Dividing {0} by {1} gives {2}" .format(value1,value2, div(value1,value2)))
```
### Execution
```sh
$ python math_sample_code.py
Adding 5 and 3 gives 8
Subtracting 5 from 3 results in 2
Multiplying 5 by 3 equals 15
Dividing 5 by 3 gives 1.6666666666666667
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


