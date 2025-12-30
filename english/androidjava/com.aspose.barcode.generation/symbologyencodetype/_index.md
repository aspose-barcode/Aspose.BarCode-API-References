---
title: SymbologyEncodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: Symbology encode type.
type: docs
weight: 67
url: /androidjava/com.aspose.barcode.generation/symbologyencodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
```
public class SymbologyEncodeType extends BaseEncodeType
```

Symbology encode type. See EncodeTypes to get instance.

--------------------

> ```
> Create symbology encode type
>  
>  SymbologyEncodeType symbologyType = EncodeTypes.GS_1_CODE_128
> ```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  BaseEncodeType  value. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Gets a classification of this symbology. |
| [getString()](#getString--) | Converts the instance of BaseEncodeType to its equivalent string representation. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Converts the instance of BaseEncodeType to its equivalent string representation. |
| [getTypeIndex()](#getTypeIndex--) | Gets an index of encode type |
| [getTypeName()](#getTypeName--) | Gets a name of encode type |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Converts the string representation of the name of a BaseEncodeType to its instance. |
| [toString()](#toString--) | Returns the name of the given BaseEncodeType as a string. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Converts the string representation of a BaseEncodeType to its instance. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Converts the string representation of a BaseEncodeType to its instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Returns a value indicating whether this instance is equal to a specified  BaseEncodeType  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | An  BaseEncodeType  value to compare to this instance. |

**Returns:**
boolean -  **true**  if obj has the same value as this instance; otherwise,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


Gets a classification of this symbology.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Converts the instance of BaseEncodeType to its equivalent string representation. The string format is: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - A string representing the complete value of the encode type
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Converts the instance of BaseEncodeType to its equivalent string representation. The string format is: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | The BaseEncodeType instance to convert |

**Returns:**
java.lang.String - A string representing the complete value of the given encode type
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Gets an index of encode type

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Gets a name of encode type

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


Converts the string representation of the name of a BaseEncodeType to its instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stringEncodeType | java.lang.String | A string containing the name of a BaseEncodeType to convert. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Returns the name of the given BaseEncodeType as a string.

**Returns:**
java.lang.String - A string representing the name of the encode type
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string in the format as "Index:-1; Name:None" to convert. |
| result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | An actual SingleEncodeType returns, when conversion has completed successfully;

otherwise it returns null. |

**Returns:**
boolean -  **true**  if s was converted successfully; otherwise,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string in the format as "Index:-1; Name:None" to convert. |
| result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | An actual SingleEncodeType returns, when conversion has completed successfully;

otherwise it returns null. |

**Returns:**
boolean -  **true**  if s was converted successfully; otherwise,  **false** .
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

