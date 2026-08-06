---
title: SymbologyEncodeType
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 符号编码类型。
type: docs
weight: 67
url: /zh/androidjava/com.aspose.barcode.generation/symbologyencodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
```
public class SymbologyEncodeType extends BaseEncodeType
```

符号编码类型。参见 EncodeTypes 获取实例。

--------------------

> ```
> Create symbology encode type
>  
>  SymbologyEncodeType symbologyType = EncodeTypes.GS_1_CODE_128
> ```
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 BaseEncodeType 值。 |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | 获取此符号的分类。 |
| [getString()](#getString--) | 将 BaseEncodeType 的实例转换为等效的字符串表示。 |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | 将 BaseEncodeType 的实例转换为等效的字符串表示。 |
| [getTypeIndex()](#getTypeIndex--) | 获取编码类型的索引 |
| [getTypeName()](#getTypeName--) | 获取编码类型的名称 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | 将 BaseEncodeType 名称的字符串表示转换为其实例。 |
| [toString()](#toString--) | 以字符串形式返回给定 BaseEncodeType 的名称。 |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | 将 BaseEncodeType 的字符串表示转换为其实例。 |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | 将 BaseEncodeType 的字符串表示转换为其实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


返回一个值，指示此实例是否等于指定的 BaseEncodeType 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 其他 | java.lang.Object | 用于与此实例比较的 BaseEncodeType 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
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


获取此符号的分类。

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


将 BaseEncodeType 实例转换为等效的字符串表示形式。字符串格式为："Index:0; Name:Codabar"。

**Returns:**
java.lang.String - 表示编码类型完整值的字符串
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


将 BaseEncodeType 实例转换为等效的字符串表示形式。字符串格式为："Index:-1; Name:None"。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | 要转换的 BaseEncodeType 实例 |

**Returns:**
java.lang.String - 表示给定编码类型完整值的字符串
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


获取编码类型的索引

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


获取编码类型的名称

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
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


将 BaseEncodeType 名称的字符串表示转换为其实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stringEncodeType | java.lang.String | 包含要转换的 BaseEncodeType 名称的字符串。 |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


以字符串形式返回给定 BaseEncodeType 的名称。

**Returns:**
java.lang.String - 表示编码类型名称的字符串
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


将 BaseEncodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 要转换的格式为 "Index:-1; Name:None" 的字符串。 |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | 当转换成功完成时，返回实际的 SingleEncodeType； |

否则返回 null。 |

**Returns:**
boolean -  **true**  表示 s 已成功转换；否则， **false** 。
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


将 BaseEncodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 要转换的格式为 "Index:-1; Name:None" 的字符串。 |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | 当转换成功完成时，返回实际的 SingleEncodeType； |

否则返回 null。 |

**Returns:**
boolean -  **true**  表示 s 已成功转换；否则， **false** 。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

