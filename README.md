# Quadratic Equations Solver
<p>The script calculates the roots of the quadratic equation.</p>
<p>ax^2 + bx + c = 0</p>
<p>Input: three coefficients of the quadratic equation.</p>
<p>get_roots (a, b, c)</p>
<p>Output: a tuple with the values of two roots</p>
<p>(root1, root2) or (root1, None) or (None, None)</p>

# How to Use

```bash
>>> from quadratic_equation import get_roots
>>> get_roots(1, 2, -3)
(-3.0, 1.0)
>>> get_roots(1, -2, 1)
(1.0, None)
>>> get_roots(1, 2, 3)
(None, None)
```

# How to Launch Tests

```bash
python tests.py
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
