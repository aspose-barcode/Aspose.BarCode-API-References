---
title: SingleDecodeType
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 单一解码类型。
type: docs
weight: 48
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

单个解码类型。参见解码类型以获取实例。

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Methods

| Method | 描述 |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 返回一个值，指示此实例是否包含在指定的列表中。 |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 值。 |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | 将 SingleDecodeType 的实例转换为其等效的字符串表示形式，使用以下格式：\"Index:-1; Name:None\"。 |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | 将 SingleDecodeType 的实例转换为其等效的字符串表示形式，使用以下格式：\"Index:-1; Name:None\"。 |
| [getTypeIndex()](#getTypeIndex--) | 获取解码类型的索引 |
| [getTypeName()](#getTypeName--) | 获取解码类型的名称 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | 将 SingleDecodeType 名称的字符串表示转换为其实例。 |
| [toString()](#toString--) | 重写的方法，将 SingleDecodeType 表示为名称字符串。 |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 将 BaseDecodeType 的字符串表示转换为其实例，在确定具体类型后。 |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | 将 MultiDecodeType 的字符串表示转换为其实例。 |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | 将 SingleDecodeType 的字符串表示转换为其实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


返回一个值，指示此实例是否包含在指定的列表中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 单个和多个解码类型的数组 |

**Returns:**
boolean - 如果包含任何类型，则值为 true
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 其他 | com.aspose.barcode.barcoderecognition.MultiDecodeType |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个 System.Object 值，用于与此实例进行比较。 |

**Returns:**
boolean - 如果对象的值与此实例相同，则为 true；否则为 false。
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


将 SingleDecodeType 的实例转换为其等效的字符串表示形式，使用以下格式：\"Index:-1; Name:None\"。

**Returns:**
java.lang.String - 表示单个解码类型完整值的字符串
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


将 SingleDecodeType 的实例转换为其等效的字符串表示形式，使用以下格式：\"Index:-1; Name:None\"。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 要转换的 SingleDecodeType 实例 |

**Returns:**
java.lang.String - 表示给定单个解码类型完整值的字符串
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


获取解码类型的索引

**Returns:**
short - 解码类型的索引
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


获取解码类型的名称

**Returns:**
java.lang.String - 解码类型的名称
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




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


将 SingleDecodeType 名称的字符串表示转换为其实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stringDecodeType | java.lang.String | 包含要转换的 SingleDecodeType 名称的字符串。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


重写的方法，将 SingleDecodeType 表示为名称字符串。

**Returns:**
java.lang.String - 表示单个解码类型名称的字符串
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


将 BaseDecodeType 的字符串表示转换为其实例，在确定具体类型后。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 MultiDecodeType 表示的字符串。 |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

否则返回不确定类型，或 MultiDecodeType（\"None\"）。
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


将 MultiDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 MultiDecodeType 表示的字符串。 |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - 当转换成功完成时返回实际的 MultiDecodeType；

否则返回不确定类型，或 MultiDecodeType（\"None\"）。
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 SingleDecodeType，格式如 \"EAN8\"、\"EAN13\"、\"CodaBar\"... 的字符串。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

否则返回不确定类型，或 SingleDecodeType（-1，\"None\"）。
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

