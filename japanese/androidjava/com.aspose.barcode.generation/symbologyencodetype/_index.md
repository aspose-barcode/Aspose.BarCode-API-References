---
title: SymbologyEncodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: シンボロジー エンコードタイプ。
type: docs
weight: 67
url: /ja/androidjava/com.aspose.barcode.generation/symbologyencodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
```
public class SymbologyEncodeType extends BaseEncodeType
```

シンボルエンコードタイプ。インスタンスを取得するには EncodeTypes を参照してください。

--------------------

> ```
> Create symbology encode type
>  
>  SymbologyEncodeType symbologyType = EncodeTypes.GS_1_CODE_128
> ```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | このインスタンスが指定された BaseEncodeType 値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | このシンボルの分類を取得します。 |
| [getString()](#getString--) | BaseEncodeType のインスタンスを同等の文字列表現に変換します。 |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | BaseEncodeType のインスタンスを同等の文字列表現に変換します。 |
| [getTypeIndex()](#getTypeIndex--) | エンコードタイプのインデックスを取得します |
| [getTypeName()](#getTypeName--) | エンコードタイプの名前を取得します |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | BaseEncodeType の名前の文字列表現をインスタンスに変換します。 |
| [toString()](#toString--) | 指定された BaseEncodeType の名前を文字列として返します。 |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | BaseEncodeType の文字列表現をインスタンスに変換します。 |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | BaseEncodeType の文字列表現をインスタンスに変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


このインスタンスが指定された BaseEncodeType 値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| その他 | java.lang.Object | このインスタンスと比較するための BaseEncodeType 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
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


このシンボルの分類を取得します。

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


BaseEncodeType のインスタンスを同等の文字列表現に変換します。文字列形式は次のとおりです: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - エンコードタイプの完全な値を表す文字列
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


BaseEncodeType のインスタンスを同等の文字列表現に変換します。文字列形式は次のとおりです: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | 変換する BaseEncodeType のインスタンス |

**Returns:**
java.lang.String - 指定されたエンコードタイプの完全な値を表す文字列
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


エンコードタイプのインデックスを取得します

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


エンコードタイプの名前を取得します

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


BaseEncodeType の名前の文字列表現をインスタンスに変換します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stringEncodeType | java.lang.String | 変換する BaseEncodeType の名前を含む文字列。 |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


指定された BaseEncodeType の名前を文字列として返します。

**Returns:**
java.lang.String - エンコードタイプの名前を表す文字列
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


BaseEncodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための文字列形式は "Index:-1; Name:None" です。 |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | 変換が正常に完了した場合、実際の SingleEncodeType が返されます; |

それ以外の場合は null を返します。 |

**Returns:**
boolean -  **true**  が s の変換に成功した場合; それ以外は **false** 。
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


BaseEncodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための文字列形式は "Index:-1; Name:None" です。 |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | 変換が正常に完了した場合、実際の SingleEncodeType が返されます; |

それ以外の場合は null を返します。 |

**Returns:**
boolean -  **true**  が s の変換に成功した場合; それ以外は **false** 。
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

