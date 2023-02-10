---
title: Distance
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 17
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/distance/
---
**Inheritance:**
java.lang.Object
```
public class Distance
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Distance()](#Distance--) |  |
## Methods

| Method | Description |
| --- | --- |
| [bitwiseHamming(byte[] x, byte[] y)](#bitwiseHamming-byte---byte---) |  |
| [bitwiseHamming(int x, int y)](#bitwiseHamming-int-int-) |  |
| [convolutionMetric(List<Byte> hypothesis, List<Byte> standard, int penalty)](#convolutionMetric-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--int-) | A metric of hypByteBlock and byteBlock |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hamming(byte[] x, byte[] y)](#hamming-byte---byte---) |  |
| [hammingDistance(List<Byte> bytes1, List<Byte> bytes2, int blockLength)](#hammingDistance-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--int-) | Hamming distance of bytes1 and bytes 2 |
| [hashCode()](#hashCode--) |  |
| [levenshtein(String x, String y)](#levenshtein-java.lang.String-java.lang.String-) |  |
| [levenshteinMax255(byte[] x, byte[] y)](#levenshteinMax255-byte---byte---) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [taxicabDistanceX(ByteBitmap byteBitmap, int x1, int x2)](#taxicabDistanceX-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-) | Calculates taxicab distance between x1 and x2 levels (Hamming 1d = taxicab distance) |
| [taxicabDistanceY(ByteBitmap byteBitmap, int y1, int y2)](#taxicabDistanceY-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-) | Calculates taxicab distance between y1 and y2 levels (Hamming 1d = taxicab distance) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Distance() {#Distance--}
```
public Distance()
```


### bitwiseHamming(byte[] x, byte[] y) {#bitwiseHamming-byte---byte---}
```
public static int bitwiseHamming(byte[] x, byte[] y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | byte[] |  |
| y | byte[] |  |

**Returns:**
int
### bitwiseHamming(int x, int y) {#bitwiseHamming-int-int-}
```
public static int bitwiseHamming(int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |

**Returns:**
int
### convolutionMetric(List<Byte> hypothesis, List<Byte> standard, int penalty) {#convolutionMetric-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--int-}
```
public static int convolutionMetric(List<Byte> hypothesis, List<Byte> standard, int penalty)
```


A metric of hypByteBlock and byteBlock

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hypothesis | java.util.List<java.lang.Byte> | Hypotesis byte block |
| standard | java.util.List<java.lang.Byte> | Byte block |
| penalty | int | Incorrect bytes coefficient |

**Returns:**
int - A metric of hypByteBlock and byteBlock
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
### hamming(byte[] x, byte[] y) {#hamming-byte---byte---}
```
public static int hamming(byte[] x, byte[] y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | byte[] |  |
| y | byte[] |  |

**Returns:**
int
### hammingDistance(List<Byte> bytes1, List<Byte> bytes2, int blockLength) {#hammingDistance-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--int-}
```
public static int hammingDistance(List<Byte> bytes1, List<Byte> bytes2, int blockLength)
```


Hamming distance of bytes1 and bytes 2

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes1 | java.util.List<java.lang.Byte> | first list of bytes |
| bytes2 | java.util.List<java.lang.Byte> | second list of bytes |
| blockLength | int | The length of the block to calculate Hamming distance on this from 0 to blockLength |

**Returns:**
int - Hamming distance
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### levenshtein(String x, String y) {#levenshtein-java.lang.String-java.lang.String-}
```
public static int levenshtein(String x, String y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | java.lang.String |  |
| y | java.lang.String |  |

**Returns:**
int
### levenshteinMax255(byte[] x, byte[] y) {#levenshteinMax255-byte---byte---}
```
public static int levenshteinMax255(byte[] x, byte[] y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | byte[] |  |
| y | byte[] |  |

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




### taxicabDistanceX(ByteBitmap byteBitmap, int x1, int x2) {#taxicabDistanceX-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-}
```
public static int taxicabDistanceX(ByteBitmap byteBitmap, int x1, int x2)
```


Calculates taxicab distance between x1 and x2 levels (Hamming 1d = taxicab distance)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte bitmap |
| x1 | int | first x-coordinate |
| x2 | int | second x-coordinate |

**Returns:**
int - taxicab distance (1d)
### taxicabDistanceY(ByteBitmap byteBitmap, int y1, int y2) {#taxicabDistanceY-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-}
```
public static int taxicabDistanceY(ByteBitmap byteBitmap, int y1, int y2)
```


Calculates taxicab distance between y1 and y2 levels (Hamming 1d = taxicab distance)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte bitmap |
| y1 | int | first y-coordinate |
| y2 | int | second y-coordinate |

**Returns:**
int - taxicab distance (1d)
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

