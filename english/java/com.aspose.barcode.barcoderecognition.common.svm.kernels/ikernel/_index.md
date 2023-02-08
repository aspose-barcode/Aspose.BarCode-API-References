---
title: IKernel
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.common.svm.kernels/ikernel/
---```
public interface IKernel
```
## Methods

| Method | Description |
| --- | --- |
| [estimateComplexity(double[][] inputs)](#estimateComplexity-double-----) |  |
| [function(double[] x, double[] y)](#function-double---double---) |  |
| [product(double a, double[] b, double[] accumulate)](#product-double-double---double---) |  |
### estimateComplexity(double[][] inputs) {#estimateComplexity-double-----}
```
public abstract double estimateComplexity(double[][] inputs)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputs | double[][] |  |

**Returns:**
double
### function(double[] x, double[] y) {#function-double---double---}
```
public abstract double function(double[] x, double[] y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double[] |  |
| y | double[] |  |

**Returns:**
double
### product(double a, double[] b, double[] accumulate) {#product-double-double---double---}
```
public abstract void product(double a, double[] b, double[] accumulate)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | double |  |
| b | double[] |  |
| accumulate | double[] |  |

