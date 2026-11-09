---
title: "AlternativeScheme"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "代替支払いスキームの指示"
type: docs
weight: 11
url: /ja/java/com.aspose.barcode.complexbarcode/alternativescheme/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class AlternativeScheme implements System.IEquatable<AlternativeScheme>
```

代替支払いスキームの指示
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AlternativeScheme()](#AlternativeScheme--) |  |
| [AlternativeScheme(String instruction)](#AlternativeScheme-java.lang.String-) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。 |
| [getClass()](#getClass--) |  |
| [getInstruction()](#getInstruction--) | 指定された請求書の支払い指示を取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setInstruction(String value)](#setInstruction-java.lang.String-) | 指定された請求書の支払い指示を取得します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AlternativeScheme() {#AlternativeScheme--}
```
public AlternativeScheme()
```


### AlternativeScheme(String instruction) {#AlternativeScheme-java.lang.String-}
```
public AlternativeScheme(String instruction)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 指示 | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 現在のオブジェクトと比較するオブジェクト。 |

**Returns:**
boolean - 指定されたオブジェクトが現在のオブジェクトと等しい場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstruction() {#getInstruction--}
```
public String getInstruction()
```


指定された請求書の支払い指示を取得します。

この指示は、スキームの2文字の省略形、区切り文字、およびパラメータのシーケンス（インデックス2の文字で区切られます）で構成されています。

値: 支払い指示。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを取得します。

**Returns:**
int - 現在のオブジェクトのハッシュコード。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setInstruction(String value) {#setInstruction-java.lang.String-}
```
public void setInstruction(String value)
```


指定された請求書の支払い指示を取得します。

この指示は、スキームの2文字の省略形、区切り文字、およびパラメータのシーケンス（インデックス2の文字で区切られます）で構成されています。

値: 支払い指示。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

