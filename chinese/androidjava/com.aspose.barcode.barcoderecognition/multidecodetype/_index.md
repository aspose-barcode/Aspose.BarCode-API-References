---
title: MultiDecodeType
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 复合解码类型。
type: docs
weight: 37
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

复合解码类型。

此示例展示了如何创建复合的 MultiDecode 类型，以组合 SingleDecodeType 和 MultiDecode 类型。

```

```
## Constructors

| Constructor | 描述 |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | 初始化 MultiDecodeType 类的新实例。 |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 初始化 MultiDecodeType 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | 向 MultiDecodeType 添加另一个 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 。 |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 检查此是否包含所有条形码类型。 |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 是否包含任何类型 |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | 返回一个值，指示此实例是否等于指定的 MultiDecodeType 值。 |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | 返回一个值，指示此解码类型集合是否仅包含指定的 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 值。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 MultiDecodeType 值。 |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | 从 MultiDecodeType 中排除 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)，并返回新的 MultiDecodeType 实例。 |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | 表示单个类型的列表。 |
| [getSingleTypesCount()](#getSingleTypesCount--) | 返回单个类型的数量。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 重写的方法，将 MultiDecodeType 表示为字符串。 |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 将 BaseDecodeType 的字符串表示转换为其实例，在确定具体类型后。 |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | 将 MultiDecodeType 的字符串表示转换为其实例。 |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | 将 SingleDecodeType 的字符串表示转换为其实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


初始化 MultiDecodeType 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 单个解码类型的数组 |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


初始化 MultiDecodeType 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 多重和单个解码类型的数组 |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


向 MultiDecodeType 添加另一个 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 要添加到列表的单个 DecodeType |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


检查此是否包含所有条形码类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 输入单个或多重条形码类型 |

**Returns:**
boolean - 如果所有类型都已包含，则值为 true
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


是否包含任何类型

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 解码类型 |

**Returns:**
boolean - 如果包含任何类型，则值为 true
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


返回一个值，指示此实例是否等于指定的 MultiDecodeType 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 其他 | com.aspose.barcode.barcoderecognition.MultiDecodeType | 用于与此实例比较的 MultiDecodeType 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


返回一个值，指示此解码类型集合是否仅包含指定的 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 用于与此解码类型集合比较的 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) 值。 |

**Returns:**
boolean -  **true**  if this collection contains only specified decode type; otherwise,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 MultiDecodeType 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个 System.Object 值，用于与此实例进行比较。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


从 MultiDecodeType 中排除 [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)，并返回新的 MultiDecodeType 实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | A Single DecodeType to be excluded. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - New MultiDecodeType instance with excluded SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


表示单个类型的列表。

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - List of single types
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


返回单个类型的数量。

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


重写的方法，将 MultiDecodeType 表示为字符串。

**Returns:**
java.lang.String - A string representing MultiDecodeType instance as "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
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

