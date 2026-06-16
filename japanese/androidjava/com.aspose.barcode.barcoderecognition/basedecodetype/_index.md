---
title: BaseDecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: MultiDecodeType と SingleDecodeType の基底クラスです。
type: docs
weight: 23
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

MultiDecodeType と SingleDecodeType の基底クラスです。

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
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 指定されたデコードタイプのいずれかが含まれているかどうかを判定します |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | このインスタンスが指定された[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)の値と等しいかどうかを示す値を返します。 |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | このインスタンスが指定された[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)の値と等しいかどうかを示す値を返します。 |
| [equals(Object other)](#equals-java.lang.Object-) | このインスタンスが指定された[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 具体的な型を決定した上で、BaseDecodeType の文字列表現をインスタンスに変換します。 |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType の文字列表現をインスタンスに変換します。 |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType の文字列表現をインスタンスに変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


指定されたデコードタイプのいずれかが含まれているかどうかを判定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 検証対象のタイプ。 |

**Returns:**
boolean - いずれかのタイプが含まれている場合は true です。
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


このインスタンスが指定された[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)の値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| その他 | com.aspose.barcode.barcoderecognition.MultiDecodeType | このインスタンスと比較するための java.lang.Object 値。 |

**Returns:**
boolean - オブジェクトがこのインスタンスと同じ値を持つ場合は true、そうでない場合は false です。
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


このインスタンスが指定された[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)の値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | このインスタンスと比較するための java.lang.Object 値。 |

**Returns:**
boolean - オブジェクトがこのインスタンスと同じ値を持つ場合は true、そうでない場合は false です。
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


このインスタンスが指定された[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)の値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| その他 | java.lang.Object | このインスタンスと比較するための java.lang.Object 値。 |

**Returns:**
boolean - オブジェクトがこのインスタンスと同じ値を持つ場合は true、そうでない場合は false です。
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


BaseDecodeType の文字列表現を具体的な型に変換し、そのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための MultiDecodeType 表現を含む文字列 |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

それ以外の場合は不定型、または MultiDecodeType ("None") を返します。
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


MultiDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための MultiDecodeType 表現を含む文字列 |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - 変換が正常に完了した場合、実際の MultiDecodeType が返されます；

それ以外の場合は不定型、または MultiDecodeType ("None") を返します。
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための "EAN8"、"EAN13"、"CodaBar" などの形式で表された SingleDecodeType を含む文字列 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

それ以外の場合は不定型、または SingleDecodeType (-1, "None") を返します。
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

