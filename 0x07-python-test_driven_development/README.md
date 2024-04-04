# Python - Test-driven development

![alt text]

This project focuses on test-driven development using `docstring` and `unittest` in Python.

## Tests :heavy_check_mark:

* [tests](./tests): This folder contains both Holberton-provided tests and additional independently-developed tests:
  * [0-add_integer.txt](./tests/0-add_integer.txt)
  * [2-matrix_divided.txt](./tests/2-matrix_divided.txt)
  * [3-say_my_name.txt](./tests/3-say_my_name.txt)
  * [4-print_square.txt](./tests/4-print_square.txt)
  * [5-text_indentation.txt](./tests/5-text_indentation.txt)
  * [6-max_integer_test.py](./tests/6-max_integer_test.py)
  * [100-matrix_mul.txt](./tests/100-matrix_mul.txt)
  * [101-lazy_matrix_mul.txt](./tests/101-lazy_matrix_mul.txt)

## Function Prototypes :floppy_disk:

Function prototypes for each task:

| File                     | Prototype                                    |
| ------------------------ | -------------------------------------------- |
| `0-add_integer.py`       | `def add_integer(a, b=98):`                  |
| `2-matrix_divided.py`    | `def matrix_divided(matrix, div):`           |
| `3-say_my_name.py`       | `def say_my_name(first_name, last_name=""):` |
| `4-print_square.py`      | `def print_square(size):`                    |
| `5-text_indentation.py`  | `def text_indentation(text):`                |
| `100-matrix_mul.py`      | `def matrix_mul(m_a, m_b):`                  |
| `101-lazy_matrix_mul.py` | `def lazy_matrix_mul(m_a, m_b):`             |
| `102-python.c`           | `void print_python_string(PyObject *p);`     |

## Tasks :page_with_curl:

### 0. Integers addition

Function to add 2 integers.

* File: [0-add_integer.py](./0-add_integer.py)
* Test File: [0-add_integer.txt](./tests/0-add_integer.txt)

### 1. Divide a matrix

Function to divide all elements of a matrix by a common divisor.

* File: [2-matrix_divided.py](./2-matrix_divided.py)
* Test File: [2-matrix_divided.txt](./tests/2-matrix_divided.txt)

### 2. Say my name

Function to print a name in the format `My name is <first name> <last name>`.

* File: [3-say_my_name.py](./3-say_my_name.py)
* Test File: [3-say_my_name.txt](./tests/3-say_my_name.txt)

### 3. Print square

Function to print a square using the `#` character.

* File: [4-print_square.py](./4-print_square.py)
* Test File: [4-print_square.txt](./tests/4-print_square.txt)

### 4. Text indentation

Function to print text with indentation.

* File: [5-text_indentation.py](./5-text_indentation.py)
* Test File: [5-text_indentation.txt](./tests/5-text_indentation.txt)

### 5. Max integer - Unittest


Unittests for the function `def max_integer(list=[]):`.

* Test File: [6-max_integer_test.py](./tests/6-max_integer_test.py)

### 6. Matrix multiplication

Function to multiply 2 matrices.

* File: [100-matrix_mul.py](./100-matrix_mul.py)
* Test File: [100-matrix_mul.txt](./tests/100-matrix_mul.txt)

### 7. Lazy matrix multiplication

Function to multiply 2 matrices using the NumPy module.

* File: [101-lazy_matrix_mul.py](./101-lazy_matrix_mul.py)
* Test File: [101-lazy_matrix_mul.txt](./tests/101-lazy_matrix_mul.txt)

### 8. CPython #3: Python Strings

Function to print Python strings.

* File: [102-python.c](./102-python.c)
