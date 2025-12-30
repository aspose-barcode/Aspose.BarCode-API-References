---
title: SingleDecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: Single decode type.
type: docs
weight: 47
url: /androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

Single decode type. See decode type to get instance.

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Methods

| Method | Description |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Returns a value indicating whether this instance is included into the list specified. |
| [equals(MultyDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultyDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) value. |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | Converts the instance of SingleDecodeType to its equivalent string representation, using the following format: "Index:-1; Name:None". |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Converts the instance of SingleDecodeType to its equivalent string representation, using the following format: "Index:-1; Name:None". |
| [getTypeIndex()](#getTypeIndex--) | Gets an index of decode type |
| [getTypeName()](#getTypeName--) | Gets a name of decode type |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | Converts the string representation of the name of a SingleDecodeType to its instance. |
| [toString()](#toString--) | Overridden method representing SingleDecodeType as the Name string. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Converts the string representation of a BaseDecodeType to its instance, having determined the concrete type. |
| [tryParseMultyDecodeType(String parsingType)](#tryParseMultyDecodeType-java.lang.String-) | Converts the string representation of a MultyDecodeType to its instance. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converts the string representation of a SingleDecodeType to its instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


Returns a value indicating whether this instance is included into the list specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array of single and multy decode types |

**Returns:**
boolean - Value is a true if any types are included into
### equals(MultyDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultyDecodeType-}
```
public boolean equals(MultyDecodeType other)
```


Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype) |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | An System.Object value to compare to this instance. |

**Returns:**
boolean - True if obj has the same value as this instance; otherwise, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getString() {#getString--}
```
public String getString()
```


Converts the instance of SingleDecodeType to its equivalent string representation, using the following format: "Index:-1; Name:None".

**Returns:**
java.lang.String - A string representing the complete value of the single decode type
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


Converts the instance of SingleDecodeType to its equivalent string representation, using the following format: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | The SingleDecodeType instance to convert |

**Returns:**
java.lang.String - A string representing the complete value of the given single decode type
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Gets an index of decode type

**Returns:**
short - The index of decode type
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Gets a name of decode type

**Returns:**
java.lang.String - The name of decode type
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




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


Converts the string representation of the name of a SingleDecodeType to its instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stringDecodeType | java.lang.String | A string containing the name of a SingleDecodeType to convert. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


Overridden method representing SingleDecodeType as the Name string.

**Returns:**
java.lang.String - A string representing the name of the single decode type
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

