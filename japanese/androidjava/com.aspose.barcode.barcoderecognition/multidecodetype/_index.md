---
title: "MultiDecodeType"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "複合デコードタイプです。"
type: docs
weight: 35
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

複合デコードタイプです。

このサンプルは、SingleDecodeType と MultiDecode タイプを組み合わせた複合 MultiDecode タイプの作成方法を示します。

```

```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | 新しいインスタンスを初期化します [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) クラスの。 |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 新しいインスタンスを初期化します [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) クラスの。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | MultiDecodeType にもう一つの [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) を追加します。 |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | これがすべてのバーコードタイプを含んでいるか確認します。 |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 任意のタイプが含まれていますか。 |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | このインスタンスが指定された [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) の値と等しいかどうかを示す値を返します。 |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | このデコードタイプコレクションが指定された [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) の値のみを含むかどうかを示す値を返します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) の値と等しいかどうかを示す値を返します。 |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) を MultiDecodeType から除外し、新しい MultiDecodeType インスタンスを返します。 |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | 単一タイプのリストを表します。 |
| [getSingleTypesCount()](#getSingleTypesCount--) | 単一タイプの数を返します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | MultiDecodeType を文字列として表すオーバーライドされたメソッドです。 |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | 具体的な型が決定された後、BaseDecodeType の文字列表現をインスタンスに変換します。 |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType の文字列表現をインスタンスに変換します。 |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType の文字列表現をインスタンスに変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


新しいインスタンスを初期化します [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) クラスの。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 単一デコードタイプの配列 |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


新しいインスタンスを初期化します [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) クラスの。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | マルチおよび単一デコードタイプの配列 |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


MultiDecodeType にもう一つの [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) を追加します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | リストに追加する単一 DecodeType |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


これがすべてのバーコードタイプを含んでいるか確認します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 単一またはマルチのバーコードタイプを入力します |

**Returns:**
boolean - すべてのタイプが含まれている場合は true です
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


任意のタイプが含まれていますか。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | デコードタイプ |

**Returns:**
boolean - 任意のタイプが含まれている場合は true です
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


このインスタンスが指定された [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) の値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | このインスタンスと比較するための [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) の値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は、  **false** 。
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


このデコードタイプコレクションが指定された [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) の値のみを含むかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | このデコードタイプコレクションと比較するための [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) の値です。 |

**Returns:**
boolean - このコレクションが指定されたデコードタイプのみを含む場合は **true**、それ以外の場合は **false** です。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) の値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための System.Object 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は、  **false** 。
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) を MultiDecodeType から除外し、新しい MultiDecodeType インスタンスを返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | 除外する単一 DecodeType |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - New MultiDecodeType instance with excluded SingleDecodeType.
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


単一タイプのリストを表します。

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - 単一タイプのリスト
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


単一タイプの数を返します。

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


MultiDecodeType を文字列として表すオーバーライドされたメソッドです。

**Returns:**
java.lang.String - MultiDecodeType インスタンスを "singleDecodeType1, singleDecodeType2, ..." の形式で表す文字列

 **"AllSupportedTypes"**  returns when all types are included.
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


BaseDecodeType の文字列表現を具体的な型を判定した上でインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換する MultiDecodeType 表現を含む文字列です。 |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

それ以外の場合は不定型を返します。または MultiDecodeType (\"None\") を返します。
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


MultiDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換する MultiDecodeType 表現を含む文字列です。 |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

それ以外の場合は不定型を返します。または MultiDecodeType (\"None\") を返します。
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための \"EAN8\"、\"EAN13\"、\"CodaBar\" などの形式の SingleDecodeType を含む文字列です。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

それ以外の場合は不定型を返します。または SingleDecodeType (-1, \"None\") を返します。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

