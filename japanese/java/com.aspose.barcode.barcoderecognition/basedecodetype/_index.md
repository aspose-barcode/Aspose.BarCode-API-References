---
title: "BaseDecodeType"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "MultiDecodeType と SingleDecodeType の基底クラスです。"
type: docs
weight: 22
url: /ja/java/com.aspose.barcode.barcoderecognition/basedecodetype/
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
## メソッド

| メソッド | 説明 |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 指定されたデコードタイプのいずれかが含まれているかどうかを判定します |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | このインスタンスが指定された [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 値と等しいかどうかを示す値を返します。 |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | このインスタンスが指定された [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 値と等しいかどうかを示す値を返します。 |
| [equals(Object other)](#equals-java.lang.Object-) | このインスタンスが指定された [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 具体的な型を判定した上で、BaseDecodeType の文字列表現をインスタンスに変換します。 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 検証対象のタイプ。 |

**Returns:**
boolean - いずれかのタイプが含まれている場合は true です。
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


このインスタンスが指定された [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | このインスタンスと比較する java.lang.Object 値。 |

**Returns:**
boolean - オブジェクトがこのインスタンスと同じ値を持つ場合は true、そうでない場合は false。
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


このインスタンスが指定された [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | このインスタンスと比較する java.lang.Object 値。 |

**Returns:**
boolean - オブジェクトがこのインスタンスと同じ値を持つ場合は true、そうでない場合は false。
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


このインスタンスが指定された [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) 値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | java.lang.Object | このインスタンスと比較する java.lang.Object 値。 |

**Returns:**
boolean - オブジェクトがこのインスタンスと同じ値を持つ場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
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


BaseDecodeType の文字列表現を具体的な型を判定した上でインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換する MultiDecodeType 表現を含む文字列。 |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

それ以外の場合は不定型、または MultiDecodeType (\"None\") を返します。
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


MultiDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換する MultiDecodeType 表現を含む文字列。 |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

それ以外の場合は不定型、または MultiDecodeType (\"None\") を返します。
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための、\"EAN8\"、\"EAN13\"、\"CodaBar\" などの形式の SingleDecodeType を含む文字列。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

それ以外の場合は不定型、または SingleDecodeType (-1, \"None\") を返します。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

