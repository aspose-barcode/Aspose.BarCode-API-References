---
title: GaloisFieldWithMultiplier
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.common.algorithms.reedsolomon.multiplier/galoisfieldwithmultiplier/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.common.algorithms.reedsolomon.GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
```
public class GaloisFieldWithMultiplier extends GaloisField
```
## Constructors

| Constructor | Description |
| --- | --- |
| [GaloisFieldWithMultiplier(int size, int multiplier)](#GaloisFieldWithMultiplier-int-int-) |  |
## Methods

| Method | Description |
| --- | --- |
| [add(int a, int b)](#add-int-int-) |  |
| [buildMonomial(int degree, int coefficient)](#buildMonomial-int-int-) |  |
| [divOne(int a)](#divOne-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAZTEC_DATA_10()](#getAZTEC-DATA-10--) |  |
| [getAZTEC_DATA_12()](#getAZTEC-DATA-12--) |  |
| [getAZTEC_DATA_6()](#getAZTEC-DATA-6--) |  |
| [getAZTEC_PARAM()](#getAZTEC-PARAM--) |  |
| [getAlpha()](#getAlpha--) |  |
| [getClass()](#getClass--) |  |
| [getDATA_AZTEC_DATA_8()](#getDATA-AZTEC-DATA-8--) |  |
| [getDATA_MATRIX_FIELD_256()](#getDATA-MATRIX-FIELD-256--) |  |
| [getDotCode_DATA_113()](#getDotCode-DATA-113--) | Create or get from cash galois field (size = 113, multiplier = 3, generator base = 1) for DotCode barcode |
| [getGeneratorBase()](#getGeneratorBase--) |  |
| [getIndex()](#getIndex--) |  |
| [getMAXICODE_FIELD_64()](#getMAXICODE-FIELD-64--) |  |
| [getOne()](#getOne--) |  |
| [getPDF417_DATA_929()](#getPDF417-DATA-929--) |  |
| [getPrimitive()](#getPrimitive--) |  |
| [getQR_CODE_FIELD_256()](#getQR-CODE-FIELD-256--) |  |
| [getSize()](#getSize--) |  |
| [getZero()](#getZero--) |  |
| [hashCode()](#hashCode--) |  |
| [multiply(int a, int b)](#multiply-int-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [substract(int a, int b)](#substract-int-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaloisFieldWithMultiplier(int size, int multiplier) {#GaloisFieldWithMultiplier-int-int-}
```
public GaloisFieldWithMultiplier(int size, int multiplier)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int |  |
| multiplier | int |  |

### add(int a, int b) {#add-int-int-}
```
public int add(int a, int b)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | int |  |
| b | int |  |

**Returns:**
int
### buildMonomial(int degree, int coefficient) {#buildMonomial-int-int-}
```
public GaloisFieldPolynomial buildMonomial(int degree, int coefficient)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | int |  |
| coefficient | int |  |

**Returns:**
[GaloisFieldPolynomial](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfieldpolynomial)
### divOne(int a) {#divOne-int-}
```
public int divOne(int a)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | int |  |

**Returns:**
int
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
### getAZTEC_DATA_10() {#getAZTEC-DATA-10--}
```
public static GaloisField getAZTEC_DATA_10()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getAZTEC_DATA_12() {#getAZTEC-DATA-12--}
```
public static GaloisField getAZTEC_DATA_12()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getAZTEC_DATA_6() {#getAZTEC-DATA-6--}
```
public static GaloisField getAZTEC_DATA_6()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getAZTEC_PARAM() {#getAZTEC-PARAM--}
```
public static GaloisField getAZTEC_PARAM()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getAlpha() {#getAlpha--}
```
public int[] getAlpha()
```




**Returns:**
int[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDATA_AZTEC_DATA_8() {#getDATA-AZTEC-DATA-8--}
```
public static GaloisField getDATA_AZTEC_DATA_8()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getDATA_MATRIX_FIELD_256() {#getDATA-MATRIX-FIELD-256--}
```
public static GaloisField getDATA_MATRIX_FIELD_256()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getDotCode_DATA_113() {#getDotCode-DATA-113--}
```
public static GaloisField getDotCode_DATA_113()
```


Create or get from cash galois field (size = 113, multiplier = 3, generator base = 1) for DotCode barcode

**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield) - 
### getGeneratorBase() {#getGeneratorBase--}
```
public int getGeneratorBase()
```




**Returns:**
int
### getIndex() {#getIndex--}
```
public int[] getIndex()
```




**Returns:**
int[]
### getMAXICODE_FIELD_64() {#getMAXICODE-FIELD-64--}
```
public static GaloisField getMAXICODE_FIELD_64()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getOne() {#getOne--}
```
public GaloisFieldPolynomial getOne()
```




**Returns:**
[GaloisFieldPolynomial](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfieldpolynomial)
### getPDF417_DATA_929() {#getPDF417-DATA-929--}
```
public static GaloisField getPDF417_DATA_929()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getPrimitive() {#getPrimitive--}
```
public int getPrimitive()
```




**Returns:**
int
### getQR_CODE_FIELD_256() {#getQR-CODE-FIELD-256--}
```
public static GaloisField getQR_CODE_FIELD_256()
```




**Returns:**
[GaloisField](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfield)
### getSize() {#getSize--}
```
public int getSize()
```




**Returns:**
int
### getZero() {#getZero--}
```
public GaloisFieldPolynomial getZero()
```




**Returns:**
[GaloisFieldPolynomial](../../com.aspose.barcode.common.algorithms.reedsolomon/galoisfieldpolynomial)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiply(int a, int b) {#multiply-int-int-}
```
public int multiply(int a, int b)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | int |  |
| b | int |  |

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




### substract(int a, int b) {#substract-int-int-}
```
public int substract(int a, int b)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | int |  |
| b | int |  |

**Returns:**
int
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

