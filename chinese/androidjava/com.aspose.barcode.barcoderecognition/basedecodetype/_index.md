---
title: BaseDecodeType
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: MultiDecodeType 和 SingleDecodeType 的基类。
type: docs
weight: 23
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

MultiDecodeType 和 SingleDecodeType 的基类。

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | 描述 |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 确定给定的解码类型中是否包含任何一个 |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | 返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。 |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | 返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。 |
| [equals(Object other)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 将 BaseDecodeType 的字符串表示转换为其实例，在确定具体类型后。 |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | 将 MultiDecodeType 的字符串表示转换为其实例。 |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | 将 SingleDecodeType 的字符串表示转换为其实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


确定给定的解码类型中是否包含任何一个

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 要验证的类型。 |

**Returns:**
boolean - 如果包含任何类型，则值为 true。
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 其他 | com.aspose.barcode.barcoderecognition.MultiDecodeType | 用于与此实例比较的 java.lang.Object 值。 |

**Returns:**
boolean - 如果对象的值与此实例相同，则为 true；否则为 false。
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 用于与此实例比较的 java.lang.Object 值。 |

**Returns:**
boolean - 如果对象的值与此实例相同，则为 true；否则为 false。
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 其他 | java.lang.Object | 用于与此实例比较的 java.lang.Object 值。 |

**Returns:**
boolean - 如果对象的值与此实例相同，则为 true；否则为 false。
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

