---
title: "MaxiCodeParameters"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "MaxiCode パラメータ。"
type: docs
weight: 55
url: /ja/androidjava/com.aspose.barcode.generation/maxicodeparameters/
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
| [getAspectRatio()](#getAspectRatio--) | 2Dバーコードモジュールの高さ/幅比率。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode のエンコードモードを取得します。 |
| [getMode()](#getMode--) | MaxiCode のエンコードモードを取得します。 |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | 構造化付加モードでの MaxiCode バーコード ID を取得します。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | 構造化付加モードでの MaxiCode バーコード数を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2Dバーコードモジュールの高さ/幅比率。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECIエンコーディングを設定します。 |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCodeエンコードモードを設定します。 |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | MaxiCodeエンコードモードを設定します。 |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | 構造化付加モードで MaxiCode バーコード ID を設定します。 |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | 構造化付加モードで MaxiCode バーコードの数を設定します。 |
| [toString()](#toString--) | この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) の人間が読める文字列表現を返します。 |
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


2Dバーコードモジュールの高さ/幅比率。

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


ECIエンコーディングを取得します。MaxiCodeEncodeModeがAutoの場合に使用されます。デフォルト値: ISO-8859-1

**Returns:**
int - ECIエンコーディング。
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


MaxiCodeエンコードモードを取得します。デフォルト値: Auto。

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


構造化付加モードで MaxiCode バーコード ID を取得します。ID は 1 から 8 の間の値でなければなりません。デフォルト値: 0

**Returns:**
int - 構造化付加モードでの MaxiCode バーコード ID
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


構造化付加モードで MaxiCode バーコードの数を取得します。カウント数は 2 から 8 の間の値（最大バーコード数）でなければなりません。デフォルト値: -1

**Returns:**
int - 構造化付加モードでの MaxiCode バーコード数
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


2Dバーコードモジュールの高さ/幅比率。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECIエンコーディングを設定します。MaxiCodeEncodeModeがAutoの場合に使用されます。デフォルト値: ISO-8859-1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | ECIエンコーディング。 |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCodeエンコードモードを設定します。デフォルト値: Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCodeエンコードモード。 |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


MaxiCodeエンコードモードを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | MaxiCodeエンコードモード。 |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


構造化付加モードで MaxiCode バーコード ID を設定します。ID は 1 から 8 の間の値でなければなりません。デフォルト値: 0

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 構造化付加モードの MaxiCode バーコード ID。 |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


構造化付加モードで MaxiCode バーコードの数を設定します。カウント数は 2 から 8 の間の値（最大バーコード数）でなければなりません。デフォルト値: -1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 構造化付加モードの MaxiCode バーコード数。 |

### toString() {#toString--}
```
public String toString()
```


この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) を表す文字列です。
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

