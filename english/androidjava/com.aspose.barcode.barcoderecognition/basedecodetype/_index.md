---
title: BaseDecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: Base class for MultyDecodeType and SingleDecodeType.
type: docs
weight: 23
url: /androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Base class for MultyDecodeType and SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultyDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultyDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Description |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Determines whether any of the given decode types is included into |
| [equals(MultyDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultyDecodeType-) | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [equals(Object other)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converts the string representation of a BaseDecodeType to its instance, having determined the concrete type. |
| [tryParseMultyDecodeType(String parsingType)](#tryParseMultyDecodeType-java.lang.String-) | Converts the string representation of a MultyDecodeType to its instance. |
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
### equals(MultyDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultyDecodeType-}
```
public boolean equals(MultyDecodeType other)
```


Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype) | An java.lang.Object value to compare to this instance. |

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
| parsingType | java.lang.String | A string containing a MultyDecodeType representation to convert. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultyDecodeType is returned, when conversion has completed successfully;

otherwise it returns indefinite type. or MultyDecodeType ("None").
### tryParseMultyDecodeType(String parsingType) {#tryParseMultyDecodeType-java.lang.String-}
```
public static MultyDecodeType tryParseMultyDecodeType(String parsingType)
```


Converts the string representation of a MultyDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string containing a MultyDecodeType representation to convert. |

**Returns:**
[MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype) - An actual MultyDecodeType is returned, when conversion has completed successfully;

otherwise it returns indefinite type. or MultyDecodeType ("None").
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
public final void wait(long arg0)
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

