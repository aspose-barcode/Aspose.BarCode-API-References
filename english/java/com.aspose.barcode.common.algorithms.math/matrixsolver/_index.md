---
title: MatrixSolver
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.common.algorithms.math/matrixsolver/
---
**Inheritance:**
java.lang.Object
```
public class MatrixSolver
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MatrixSolver()](#MatrixSolver--) |  |
## Methods

| Method | Description |
| --- | --- |
| [add(double[][] Mat1, double[][] Mat2)](#add-double-----double-----) | Returns the summation of two matrices with compatible dimensions. |
| [det(double[][] Mat)](#det-double-----) | Returns the determinant of a matrix with [n,n] dimension. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [inverse(double[][] Mat)](#inverse-double-----) | Returns the inverse of a matrix with [n,n] dimension and whose determinant is not zero. |
| [multiply(double[][] Mat1, double[][] Mat2)](#multiply-double-----double-----) | Returns the multiplication of two matrices with compatible dimensions. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [subtract(double[][] Mat1, double[][] Mat2)](#subtract-double-----double-----) | Returns the difference of two matrices with compatible dimensions. |
| [toString()](#toString--) |  |
| [transpose(double[][] Mat)](#transpose-double-----) | Returns the transpose of a matrix. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MatrixSolver() {#MatrixSolver--}
```
public MatrixSolver()
```


### add(double[][] Mat1, double[][] Mat2) {#add-double-----double-----}
```
public static double[][] add(double[][] Mat1, double[][] Mat2)
```


Returns the summation of two matrices with compatible dimensions. In case of an error the error is raised as an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Mat1 | double[][] | First array in the summation |
| Mat2 | double[][] | Second array in the summation |

**Returns:**
double[][] - Sum of Mat1 and Mat2 as an array
### det(double[][] Mat) {#det-double-----}
```
public static double det(double[][] Mat)
```


Returns the determinant of a matrix with [n,n] dimension. In case of an error the error is raised as an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Mat | double[][] | Array with [n,n] dimension whose determinant is to be found |

**Returns:**
double - Determinant of the array
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
### inverse(double[][] Mat) {#inverse-double-----}
```
public static double[][] inverse(double[][] Mat)
```


Returns the inverse of a matrix with [n,n] dimension and whose determinant is not zero. In case of an error the error is raised as an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Mat | double[][] | Array with [n,n] dimension whose inverse is to be found |

**Returns:**
double[][] - Inverse of the array as an array
### multiply(double[][] Mat1, double[][] Mat2) {#multiply-double-----double-----}
```
public static double[][] multiply(double[][] Mat1, double[][] Mat2)
```


Returns the multiplication of two matrices with compatible dimensions. In case of an error the error is raised as an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Mat1 | double[][] | First array in multiplication |
| Mat2 | double[][] | Second array in multiplication |

**Returns:**
double[][] - Mat1 multiplied by Mat2 as an array
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### subtract(double[][] Mat1, double[][] Mat2) {#subtract-double-----double-----}
```
public static double[][] subtract(double[][] Mat1, double[][] Mat2)
```


Returns the difference of two matrices with compatible dimensions. In case of an error the error is raised as an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Mat1 | double[][] | First array in the subtraction |
| Mat2 | double[][] | Second array in the subtraction |

**Returns:**
double[][] - Difference of Mat1 and Mat2 as an array
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transpose(double[][] Mat) {#transpose-double-----}
```
public static double[][] transpose(double[][] Mat)
```


Returns the transpose of a matrix. In case of an error the error is raised as an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Mat | double[][] | Array whose transpose is to be found |

**Returns:**
double[][] - Transpose of the array as an array
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

