---
title: SingleDecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: Single decode type.
type: docs
weight: 48
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

単一デコードタイプです。インスタンスを取得するにはデコードタイプを参照してください。

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Methods

| Method | Description |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | このインスタンスが指定されたリストに含まれているかどうかを示す値を返します。 |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | SingleDecodeType のインスタンスを、次の形式の等価な文字列表現に変換します：\"Index:-1; Name:None\"。 |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | SingleDecodeType のインスタンスを、次の形式の等価な文字列表現に変換します：\"Index:-1; Name:None\"。 |
| [getTypeIndex()](#getTypeIndex--) | デコードタイプのインデックスを取得します |
| [getTypeName()](#getTypeName--) | デコードタイプの名前を取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | SingleDecodeType の名前の文字列表現をインスタンスに変換します。 |
| [toString()](#toString--) | SingleDecodeType を名前文字列として表すオーバーライドされたメソッドです。 |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 具体的な型を決定した上で、BaseDecodeType の文字列表現をインスタンスに変換します。 |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType の文字列表現をインスタンスに変換します。 |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType の文字列表現をインスタンスに変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


このインスタンスが指定されたリストに含まれているかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 単一およびマルチデコードタイプの配列 |

**Returns:**
boolean - いずれかのタイプが含まれている場合は true です
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


このインスタンスが指定された[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)の値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| その他 | com.aspose.barcode.barcoderecognition.MultiDecodeType |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


このインスタンスが指定された[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)の値と等しいかどうかを示す値を返します。

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


このインスタンスが指定された[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)の値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための System.Object 値です。 |

**Returns:**
boolean - オブジェクトがこのインスタンスと同じ値を持つ場合は true、そうでない場合は false です。
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


SingleDecodeType のインスタンスを、次の形式の等価な文字列表現に変換します：\"Index:-1; Name:None\"。

**Returns:**
java.lang.String - 単一デコードタイプの完全な値を表す文字列
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


SingleDecodeType のインスタンスを、次の形式の等価な文字列表現に変換します：\"Index:-1; Name:None\"。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 変換対象の SingleDecodeType インスタンス |

**Returns:**
java.lang.String - 指定された単一デコードタイプの完全な値を表す文字列
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


デコードタイプのインデックスを取得します

**Returns:**
short - デコードタイプのインデックス
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


デコードタイプの名前を取得します

**Returns:**
java.lang.String - デコードタイプの名前
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
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


SingleDecodeType の名前の文字列表現をインスタンスに変換します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stringDecodeType | java.lang.String | 変換する SingleDecodeType の名前を含む文字列です。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


SingleDecodeType を名前文字列として表すオーバーライドされたメソッドです。

**Returns:**
java.lang.String - 単一デコードタイプの名前を表す文字列
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

