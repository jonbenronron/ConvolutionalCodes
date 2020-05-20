# F2Polynomials

## Description

Python file that adds polynomials over field F_2 to numpy.polynomials library.

## Documentation

### Class F2Polynomial

  Coefficients will be given in list or tuple format as an parameter.
  
  #### Parameters:
  ```
  self
  coef
  ```
  
  #### Methods:
  
  _Initialization_:
  ```
  __init__(self, coef):
  return F2Polynomial
  ```
  
  _String format_:
  ```
  __str__(self):
  return String
  ```
  
  _Degree of the polynom_:
  ```
  degree(self):
  return int
  ```
  
  #### Example:
  
  ```
  p = F2Polynomial((1,2,3))
  print(str(p))
  ```
  
  will print out:
  
  `1 + D^2`

### Functions

#### polyAdd

#### polyMul

#### polyDiv

## State
- [x] `F2Polynomial`
  - [x] `__init__`
  - [x] `__str__`
  - [x] `degree`
- [x] `polyAdd`
- [x] `polyMul`
- [ ] `polyDiv`
