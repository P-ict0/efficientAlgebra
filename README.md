# Efficient algebra

Python program to perform algebra operations using efficient algorithms like Karatsuba's algorithm for multiplication or Extended Euclidean Algorithm for gcd.
Can operate with numbers from radix 2 to radix 16. Without converting between radix in each operation. <br> <br>
_**Each number has to be inputted and will be returned as a string, except the radix.**_

## Supported operations: 
    
    - Addition
    - Subtraction 
    - Multiplication (Normal "primary school method" + Karatsuba algorithm)
    - Division
    - GCD of 2 numbers (Extended Euclidean algorithm)
    - Modular Arithmetic:
        - Reduction
        - Addition
        - Subtraction
        - Multiplication
        - Inversion

<hr>

# Getting Started
Run python on the same folder as the program and run 
```python
import efficientAlgebra
```
Then, on the same terminal you can perform operations like:
```python
efficientAlgebra.karatsuba("364da","-13f", 16)
```
The output is not formatted yet in a readable way, look into the code for details about this.
