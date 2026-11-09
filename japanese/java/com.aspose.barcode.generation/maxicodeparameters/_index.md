---
title: "MaxiCodeParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "MaxiCode パラメータ。"
type: docs
weight: 55
url: /ja/java/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode パラメータ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率です。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode のエンコードモードを取得します。 |
| [getMode()](#getMode--) | MaxiCode のエンコードモードを取得します。 |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | 構造化付加モードでの MaxiCode バーコード ID を取得します。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | 構造化付加モードでの MaxiCode バーコード数を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率です。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode エンコードモードを設定します。 |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | MaxiCode エンコードモードを設定します。 |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | 構造化付加モードで MaxiCode バーコード ID を設定します。 |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | 構造化付加モードで MaxiCode バーコードの数を設定します。 |
| [toString()](#toString--) | この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) の人間可読文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D バーコードモジュールの高さ/幅比率です。

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI エンコーディングを取得します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1

**Returns:**
int - ECI エンコーディング。
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


MaxiCode エンコードモードを取得します。デフォルト値: Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


MaxiCode のエンコードモードを取得します。

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


構造化付加モードで MaxiCode バーコード ID を取得します。ID は 1 から 8 の間の値である必要があります。デフォルト値: 0

**Returns:**
int - 構造化付加モードでの MaxiCode バーコード ID。
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


構造化付加モードで MaxiCode バーコードの数を取得します。カウントは 2 から 8 の間の値である必要があります（最大バーコード数）。デフォルト値: -1

**Returns:**
int - 構造化付加モードでの MaxiCode バーコード数。
### hashCode() {#hashCode--}
```
public final int hashCode()
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D バーコードモジュールの高さ/幅比率です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI エンコーディングを設定します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | ECI エンコーディング。 |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode エンコードモードを設定します。デフォルト値: Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode エンコードモード。 |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


MaxiCode エンコードモードを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | MaxiCode エンコードモード。 |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


構造化付加モードで MaxiCode バーコード ID を設定します。ID は 1 から 8 の間の値である必要があります。デフォルト値: 0

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 構造化追加モードの MaxiCode バーコード ID。 |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


構造化追加モードで MaxiCode バーコードの数を設定します。カウント数は 2 から 8 の間の値でなければなりません（最大バーコード数）。デフォルト値: -1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 構造化追加モードの MaxiCode バーコード数。 |

### toString() {#toString--}
```
public String toString()
```


この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) の人間可読文字列表現を返します。

**Returns:**
java.lang.String - この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) を表す文字列です。
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

