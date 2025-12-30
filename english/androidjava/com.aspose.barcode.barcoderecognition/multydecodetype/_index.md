---
title: MultyDecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: Composite decode type.
type: docs
weight: 37
url: /androidjava/com.aspose.barcode.barcoderecognition/multydecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultyDecodeType extends BaseDecodeType
```

Composite decode type.

--------------------

> ```
> CreateThis sample shows how to create compound MultyDecode types that combine SingleDecodeType and MultiDecode types.
>  
>  MultyDecodeType types1 = new MultyDecodeType(DecodeType.QR, DecodeType.DATA_MATRIX);
>  MultyDecodeType types2 = new MultyDecodeType(types1, DecodeType.CODE_128, DecodeType.CODE_39);
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MultyDecodeType(BaseDecodeType[] barcodeTypes)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Initializes a new instance of the  MultyDecodeType  class. |
| [MultyDecodeType(SingleDecodeType[] barcodeTypes)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Initializes a new instance of the  MultyDecodeType  class. |
## Methods

| Method | Description |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Adds one more [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) to the MultyDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Check if this contains all types from barcode types. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Is contain any of types |
| [equals(MultyDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultyDecodeType-) | Returns a value indicating whether this instance is equal to a specified  value. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Returns a value indicating whether this decode types collection contains only specified  value. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  MultyDecodeType  value. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Excludes  SingleDecodeType  from the MultyDecodeType and returns new MultyDecodeType instance. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Represents a list of single types. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Returns a number of single types. |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Overridden method representing MultyDecodeType as a string. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converts the string representation of a BaseDecodeType to its instance, having determined the concrete type. |
| [tryParseMultyDecodeType(String parsingType)](#tryParseMultyDecodeType-java.lang.String-) | Converts the string representation of a MultyDecodeType to its instance. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converts the string representation of a SingleDecodeType to its instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultyDecodeType(BaseDecodeType[] barcodeTypes) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultyDecodeType(BaseDecodeType[] barcodeTypes)
```


Initializes a new instance of the  MultyDecodeType  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array of single decode types |

### MultyDecodeType(SingleDecodeType[] barcodeTypes) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultyDecodeType(SingleDecodeType[] barcodeTypes)
```


Initializes a new instance of the  MultyDecodeType  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Array of multy and single decode types |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public void add(SingleDecodeType singleType)
```


Adds one more [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) to the MultyDecodeType.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | A Single DecodeType to be added to the list |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Check if this contains all types from barcode types.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Input single or multy barcode types |

**Returns:**
boolean - True if all types are included into
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Is contain any of types

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Decode types |

**Returns:**
boolean - Value is a true if any types are included into
### equals(MultyDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultyDecodeType-}
```
public boolean equals(MultyDecodeType other)
```


Returns a value indicating whether this instance is equal to a specified  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype) | An java.lang.Object value to compare to this instance. |

**Returns:**
boolean - 
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Returns a value indicating whether this decode types collection contains only specified  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | An java.lang.Object value to compare to this instance. |

**Returns:**
boolean - if this collection contains only specified decode type; otherwise, **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified  MultyDecodeType  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | An  MultyDecodeType  value to compare to this instance. |

**Returns:**
boolean - True if obj has the same value as this instance; otherwise, false.
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public MultyDecodeType exclude(SingleDecodeType singleType)
```


Excludes  SingleDecodeType  from the MultyDecodeType and returns new MultyDecodeType instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | A Single DecodeType to be excluded. |

**Returns:**
[MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype) - New MultyDecodeType instance with excluded SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public List<SingleDecodeType> getSingleTypes()
```


Represents a list of single types.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - List of single types
### getSingleTypesCount() {#getSingleTypesCount--}
```
public int getSingleTypesCount()
```


Returns a number of single types.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this instance.

**Returns:**
int - A 32-bit signed integer hash code.
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


Overridden method representing MultyDecodeType as a string.

**Returns:**
java.lang.String - A string representing MultyDecodeType instance as "singleDecodeType1, singleDecodeType2, ..."

returns when all types are included.
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
| parsingType | java.lang.String | A string in the format as either "AllSupportedTypes" or "EAN8,EAN13,CodaBar" to convert. |

**Returns:**
[MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype) - An actual MultyDecodeType is returned, when conversion has completed successfully;

otherwise it returns indefinite type. or MultyDecodeType ("NONE").
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

