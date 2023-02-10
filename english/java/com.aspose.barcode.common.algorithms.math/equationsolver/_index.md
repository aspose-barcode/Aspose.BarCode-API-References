---
title: EquationSolver
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.common.algorithms.math/equationsolver/
---
**Inheritance:**
java.lang.Object
```
public class EquationSolver
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EquationSolver()](#EquationSolver--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [solve(double[][] matrix, double[][] rightSide)](#solve-double-----double-----) | Returns the solution matrix if the matrix is square or the least squares solution otherwise. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EquationSolver() {#EquationSolver--}
```
public EquationSolver()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### solve(double[][] matrix, double[][] rightSide) {#solve-double-----double-----}
```
public static double[][] solve(double[][] matrix, double[][] rightSide)
```


Returns the solution matrix if the matrix is square or the least squares solution otherwise. Formula = (A' \* A) ^ -1 \* A' \* RS

--------------------

> ```
> // Create a matrix. Please note that this matrix
>  // is singular (i.e. not invertible), so only a 
>  // least squares solution would be feasible here.
>  double[][] matrix = new double[][]
>  {
>    {1.0, 2.0, 3.0},
>    {4.0, 5.0, 6.0},
>   {7.0, 8.0, 9.0},
>  };
>  // Define a right side matrix b:
>  double[][] rightSide = { {1}, {2}, {3} };
>  // Solve the linear system Ax = b by finding x:
>  double[,] x = Matrix.Solve(matrix, rightSide, leastSquares: true);
>  // The answer should be { {-1/18}, {2/18}, {5/18} }.
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | double[][] | The matrix for the linear problem. |
| rightSide | double[][] | The right side  b . |

**Returns:**
double[][]
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

