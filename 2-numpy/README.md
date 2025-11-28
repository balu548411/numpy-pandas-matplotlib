# NumPy Tutorials

This directory contains comprehensive tutorials and examples for NumPy (Numerical Python), the fundamental package for scientific computing in Python.

## What is NumPy?

NumPy is a powerful library that provides:
- Efficient N-dimensional array objects
- Tools for working with arrays
- Mathematical functions for array operations
- Linear algebra, Fourier transform, and random number capabilities

## Why Use NumPy?

NumPy arrays are more efficient than Python lists for numerical computations because:
- They are stored in contiguous memory locations
- They are homogeneous (all elements of the same type)
- They support vectorized operations
- They are implemented in C, making them significantly faster

## Contents

### 1_NumPy.ipynb
Introduction to NumPy covering:
- What NumPy is and why it's important
- Creating arrays using various methods
- Array properties and attributes
- Basic array operations
- Indexing and slicing techniques

### 2_NumPy.ipynb
Advanced NumPy topics including:
- Mathematical functions and operations
- Array manipulation methods
- Broadcasting concepts
- Linear algebra operations
- Random number generation
- Practical exercises

## Getting Started

### Prerequisites

Make sure you have NumPy installed:

```bash
pip install numpy
```

### Running the Tutorials

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open the notebook files in order (1_NumPy.ipynb, then 2_NumPy.ipynb)

3. Run each cell sequentially to follow along with the examples

## Key Concepts Covered

### Array Creation
- Creating arrays from lists
- Using built-in functions (zeros, ones, arange, linspace)
- Creating arrays with specific data types

### Array Operations
- Element-wise operations
- Mathematical operations (addition, subtraction, multiplication, division)
- Universal functions (ufuncs)
- Aggregation functions (sum, mean, max, min)

### Indexing and Slicing
- Basic indexing
- Boolean indexing
- Fancy indexing
- Multi-dimensional array slicing

### Array Manipulation
- Reshaping arrays
- Concatenating arrays
- Splitting arrays
- Transposing arrays

### Broadcasting
- Understanding broadcasting rules
- Using broadcasting for efficient operations
- Common broadcasting patterns

### Linear Algebra
- Matrix multiplication
- Dot product
- Matrix operations
- Solving linear equations

### Random Numbers
- Generating random numbers
- Random distributions
- Setting random seeds
- Random sampling

## Best Practices

1. **Import Convention**: Always import NumPy as `np`:
   ```python
   import numpy as np
   ```

2. **Use Vectorized Operations**: Prefer NumPy operations over Python loops for better performance

3. **Understand Data Types**: Be aware of NumPy's data types (int32, float64, etc.) for memory efficiency

4. **Broadcasting**: Learn to leverage broadcasting to write concise and efficient code

## Additional Resources

- [NumPy Official Documentation](https://numpy.org/doc/)
- [NumPy User Guide](https://numpy.org/doc/stable/user/index.html)
- [NumPy API Reference](https://numpy.org/doc/stable/reference/)

## Next Steps

After completing the NumPy tutorials, proceed to the Pandas tutorials in the `3-pandas/` directory, as Pandas is built on top of NumPy and uses NumPy arrays internally.

