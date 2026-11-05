---
title: "MultyDecodeType"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: 
type: docs
weight: 36
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/multydecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultyDecodeType extends BaseDecodeType
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MultyDecodeType(BaseDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [MultyDecodeType(SingleDecodeType[] arg0)](#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(SingleDecodeType arg0)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [containsAll(BaseDecodeType[] arg0)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [containsAny(BaseDecodeType[] arg0)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) |  |
| [describeContents()](#describeContents--) |  |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | 返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。 |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | 返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGetSingleTypesCount()](#getGetSingleTypesCount--) |  |
| [getSingleTypes()](#getSingleTypes--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 将 BaseDecodeType 的字符串表示转换为其实例，在确定具体类型后。 |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | 将 MultiDecodeType 的字符串表示转换为其实例。 |
| [tryParseMultyDecodeType(String arg0)](#tryParseMultyDecodeType-java.lang.String-) |  |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | 将 SingleDecodeType 的字符串表示转换为其实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel arg0, int arg1)](#writeToParcel-android.os.Parcel-int-) |  |
### MultyDecodeType(BaseDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultyDecodeType(BaseDecodeType[] arg0)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### MultyDecodeType(SingleDecodeType[] arg0) {#MultyDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultyDecodeType(SingleDecodeType[] arg0)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BaseDecodeType> CREATOR
```


### add(SingleDecodeType arg0) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public void add(SingleDecodeType arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

### containsAll(BaseDecodeType[] arg0) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAll(BaseDecodeType[] arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

**Returns:**
布尔
### containsAny(BaseDecodeType[] arg0) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] arg0)
```


确定给定的任何解码类型是否包含在内

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

**Returns:**
布尔
### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
整数
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | 用于与此实例比较的 java.lang.Object 值。 |

**Returns:**
boolean - 如果 obj 与此实例具有相同的值，则为 true；否则为 false。
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 用于与此实例比较的 java.lang.Object 值。 |

**Returns:**
boolean - 如果 obj 与此实例具有相同的值，则为 true；否则为 false。
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```


返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGetSingleTypesCount() {#getGetSingleTypesCount--}
```
public int getGetSingleTypesCount()
```




**Returns:**
整数
### getSingleTypes() {#getSingleTypes--}
```
public List<SingleDecodeType> getSingleTypes()
```




**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType>
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
整数
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 MultiDecodeType 表示的字符串。 |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

否则返回不确定类型，或 MultiDecodeType（"None"）。
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


将 MultiDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 MultiDecodeType 表示的字符串。 |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

否则返回不确定类型，或 MultiDecodeType（"None"）。
### tryParseMultyDecodeType(String arg0) {#tryParseMultyDecodeType-java.lang.String-}
```
public static MultyDecodeType tryParseMultyDecodeType(String arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.String |  |

**Returns:**
com.aspose.barcode.barcoderecognition.MultyDecodeType
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 SingleDecodeType，格式如 "EAN8"、"EAN13"、"CodaBar"... 的字符串。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

否则返回不确定类型，或 SingleDecodeType（-1, "None"）。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | 整数 |  |

### writeToParcel(Parcel arg0, int arg1) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | android.os.Parcel |  |
| arg1 | 整数 |  |

