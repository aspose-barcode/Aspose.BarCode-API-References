---
title: BaseDecodeType
second_title: Aspose.BarCode for Java API Reference
description: Base class for MultiDecodeType and SingleDecodeType.
type: docs
weight: 23
url: /java/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Base class for MultiDecodeType and SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Description |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Determines whether any of the given decode types is included into |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [equals(Object other)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converts the string representation of a BaseDecodeType to its instance, having determined the concrete type. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converts the string representation of a MultiDecodeType to its instance. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converts the string representation of a SingleDecodeType to its instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Determines whether any of the given decode types is included into

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Types to verify. |

**Returns:**
boolean - Value is a true if any types are included into.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | An java.lang.Object value to compare to this instance. |

**Returns:**
boolean - True if obj has the same value as this instance; otherwise, false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | An java.lang.Object value to compare to this instance. |

**Returns:**
boolean - True if obj has the same value as this instance; otherwise, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | An java.lang.Object value to compare to this instance. |

**Returns:**
boolean - True if obj has the same value as this instance; otherwise, false.
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Converts the string representation of a BaseDecodeType to its instance, having determined the concrete type. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string containing a MultiDecodeType representation to convert. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

otherwise it returns indefinite type. or MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Converts the string representation of a MultiDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string containing a MultiDecodeType representation to convert. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

otherwise it returns indefinite type. or MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string containing a SingleDecodeType in the format as "EAN8" or "EAN13" or "CodaBar"... to convert. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

otherwise it returns indefinite type. or SingleDecodeType (-1, "None").
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

