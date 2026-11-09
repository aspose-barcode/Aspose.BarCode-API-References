---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "4ステート Royal Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 24
url: /ja/java/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

4ステート Royal Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | MailmarkCodetext クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | バーコードのタイプを取得します。 |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null または Test "1" - 1C（小売） "2" - 2C（小売） "3" - 3C（小売） "4" - プレミアム（RetailPublishing Mail）（将来の使用の可能性あり） "5" - デファード（小売） "6" - エア（小売）（将来の使用の可能性あり） "7" - サーフェス（小売）（将来の使用の可能性あり） "8" - プレミアム（ネットワークアクセス） "9" - スタンダード（ネットワークアクセス） |
| [getConstructedCodetext()](#getConstructedCodetext--) | Mailmark データからコードテキストを構築します。 |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC と DP は PAF フォーマットに準拠している必要があります。 |
| [getFormat()](#getFormat--) | "0" \\u2013 Null または Test "1" \\u2013 レター "2" \\u2013 大文字 |
| [getItemID()](#getItemID--) | 最大値は 99999999 です。 |
| [getSupplychainID()](#getSupplychainID--) | Barcode C の最大値は 99、Barcode L の最大値は 999999 です。 |
| [getVersionID()](#getVersionID--) | 現在 "1" \\u2013 Mailmark バーコード用 (0 と 2 から 9 と A から Z は将来の使用のために予備) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 構築された codetext から Mailmark データを初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null または Test "1" - 1C（小売） "2" - 2C（小売） "3" - 3C（小売） "4" - プレミアム（RetailPublishing Mail）（将来の使用の可能性あり） "5" - デファード（小売） "6" - エア（小売）（将来の使用の可能性あり） "7" - サーフェス（小売）（将来の使用の可能性あり） "8" - プレミアム（ネットワークアクセス） "9" - スタンダード（ネットワークアクセス） |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC と DP は PAF フォーマットに準拠している必要があります。 |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null または Test "1" \\u2013 レター "2" \\u2013 大文字 |
| [setItemID(int value)](#setItemID-int-) | 最大値は 99999999 です。 |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Barcode C の最大値は 99、Barcode L の最大値は 999999 です。 |
| [setVersionID(int value)](#setVersionID-int-) | 現在 "1" \\u2013 Mailmark バーコード用 (0 と 2 から 9 と A から Z は将来の使用のために予備) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


MailmarkCodetext クラスの新しいインスタンスを初期化します。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


バーコードのタイプを取得します。

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Null または Test "1" - 1C（小売） "2" - 2C（小売） "3" - 3C（小売） "4" - プレミアム（RetailPublishing Mail）（将来の使用の可能性あり） "5" - デファード（小売） "6" - エア（小売）（将来の使用の可能性あり） "7" - サーフェス（小売）（将来の使用の可能性あり） "8" - プレミアム（ネットワークアクセス） "9" - スタンダード（ネットワークアクセス）

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Mailmark データからコードテキストを構築します。

**Returns:**
java.lang.String - 構築されたコードテキスト
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC と DP は PAF 形式に準拠する必要があります。国際的な "XY11 "（末尾に 5 つのスペースがあることに注意）を示す 9 文字の文字列、または国内の仕分けコードを示す文字パターンのいずれかです。国内の仕分けコードは、外部郵便番号、内部郵便番号、そして配達ポイントサフィックスで構成されます。

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null または Test "1" \\u2013 レター "2" \\u2013 大文字

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


最大値は 99999999 です。

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Barcode C の最大値は 99、Barcode L の最大値は 999999 です。

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


現在 "1" \\u2013 Mailmark バーコード用 (0 と 2 から 9 と A から Z は将来の使用のために予備)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


構築された codetext から Mailmark データを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 構築されたコードテキスト。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Null または Test "1" - 1C（小売） "2" - 2C（小売） "3" - 3C（小売） "4" - プレミアム（RetailPublishing Mail）（将来の使用の可能性あり） "5" - デファード（小売） "6" - エア（小売）（将来の使用の可能性あり） "7" - サーフェス（小売）（将来の使用の可能性あり） "8" - プレミアム（ネットワークアクセス） "9" - スタンダード（ネットワークアクセス）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC と DP は PAF 形式に準拠する必要があります。国際的な "XY11 "（末尾に 5 つのスペースがあることに注意）を示す 9 文字の文字列、または国内の仕分けコードを示す文字パターンのいずれかです。国内の仕分けコードは、外部郵便番号、内部郵便番号、そして配達ポイントサフィックスで構成されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null または Test "1" \\u2013 レター "2" \\u2013 大文字

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


最大値は 99999999 です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Barcode C の最大値は 99、Barcode L の最大値は 999999 です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


現在 "1" \\u2013 Mailmark バーコード用 (0 と 2 から 9 と A から Z は将来の使用のために予備)

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

