---
title: ECIEncoder
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 15
url: /androidjava/com.aspose.barcode/eciencoder/
---
**Inheritance:**
java.lang.Object
```
public class ECIEncoder
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ECIEncoder()](#ECIEncoder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [canBeEncoded(int eciEncoding, String str)](#canBeEncoded-int-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncodedBytes(int eciEncoding, String str)](#getEncodedBytes-int-java.lang.String-) |  |
| [getEncodedString(int eciEncoding, String str)](#getEncodedString-int-java.lang.String-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [splitToEciPiecesAuto(String codetext, int defaultEciEncoding, int eciEncoding)](#splitToEciPiecesAuto-java.lang.String-int-int-) |  |
| [splitToEciPiecesExtendedCodetext(String codetext, int defaultEciEncoding)](#splitToEciPiecesExtendedCodetext-java.lang.String-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ECIEncoder() {#ECIEncoder--}
```
public ECIEncoder()
```


### canBeEncoded(int eciEncoding, String str) {#canBeEncoded-int-java.lang.String-}
```
public static boolean canBeEncoded(int eciEncoding, String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eciEncoding | int |  |
| str | java.lang.String |  |

**Returns:**
boolean
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
### getEncodedBytes(int eciEncoding, String str) {#getEncodedBytes-int-java.lang.String-}
```
public static System.Collections.Generic.List<Byte> getEncodedBytes(int eciEncoding, String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eciEncoding | int |  |
| str | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Byte>
### getEncodedString(int eciEncoding, String str) {#getEncodedString-int-java.lang.String-}
```
public static String getEncodedString(int eciEncoding, String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eciEncoding | int |  |
| str | java.lang.String |  |

**Returns:**
java.lang.String
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




### splitToEciPiecesAuto(String codetext, int defaultEciEncoding, int eciEncoding) {#splitToEciPiecesAuto-java.lang.String-int-int-}
```
public static System.Collections.Generic.List<ECIEncoder.EciPiece> splitToEciPiecesAuto(String codetext, int defaultEciEncoding, int eciEncoding)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String |  |
| defaultEciEncoding | int |  |
| eciEncoding | int |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.ECIEncoder.EciPiece>
### splitToEciPiecesExtendedCodetext(String codetext, int defaultEciEncoding) {#splitToEciPiecesExtendedCodetext-java.lang.String-int-}
```
public static System.Collections.Generic.List<ECIEncoder.EciPiece> splitToEciPiecesExtendedCodetext(String codetext, int defaultEciEncoding)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String |  |
| defaultEciEncoding | int |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.ECIEncoder.EciPiece>
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

