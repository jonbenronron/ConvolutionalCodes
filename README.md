# F2Polynomials

## Description

Python file for [polynomials](https://numpy.org/devdocs/reference/routines.polynomials.polynomial.html) over field [Z/2Z](https://en.wikipedia.org/wiki/GF(2)).

## Documentation

### Class F2Polynomial

  F2Polynomial class will inherit the Polynomial Class from numpy.polynomial.polynimal.
  
  #### Parameters:
  ```
  self
  coef  # tuple or list
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
  
  _Degree of the polynomial_:
  ```
  degree(self):
  return int
  ```
  
  _Addition operator_ `+`:
  ```
  __add__(self, other):
  return self + other
  ```
  
  _Addition operator_ `+=`:
  ```
  __iadd__(self, other):
  return self + other
  ```
  
  _Multiplication operator_ `*`:
  ```
  __mul__(self, other):
  return self * other
  ```
  
  _Multiplication operator_ `*=`:
  ```
  __imul__(self, other):
  return self * other
  ```
  
  _Power operator_ `**`:
  ```
  __mul__(self, power):
  return self ** power
  ```
  
  #### Example:
  
  ```
  p = F2Polynomial((1, 2, 3, 4, 5, 6, 7))
  print(str(p))
  ```
  
  will print out:
  
  `1 + D^2 + D^4 + D^6`

### Functions

#### polyAdd:

Function will take two F2Polynomial objects as its parameters. Calculates the addition of given polynomials. Returns a new instance of a F2Polynomial object.

```
polyAdd(p1, p2):
return p1 + p2
```

#### polyMul:

Function will take two F2Polynomial objects as its parameters. Calculates the product of given polynomials. Returns a new instance of a F2Polynomial object.

```
polyMul(p1, p2):
return p1 * p2
```

#### polyDiv:

Function will take two F2Polynomial objects as its parameters. Calculates the division of given polynomials. Returns a new instance of a F2Polynomial object.

```
polyDiv(p1, p2):
return p1 / p2
```

## State
- [x] `F2Polynomial`
  - [x] `__init__`
  - [x] `__str__`
  - [x] `degree`
- [x] `polyAdd`
- [x] `polyMul`
- [ ] `polyDiv`
