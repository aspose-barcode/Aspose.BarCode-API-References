---
title: MaxiCodeParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: MaxiCode パラメータ。
type: docs
weight: 57
url: /ja/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode パラメータ。
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode エンコードモードを取得します。 |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | MaxiCode エンコードモードを取得します。 |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | MaxiCode エンコードモードを取得します。 |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | 構造化付加モードでの MaxiCode バーコード ID を取得します。 |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | 構造化付加モードでの MaxiCode バーコードの数を取得します。 |
| [getMode()](#getMode--) | MaxiCode エンコードモードを取得します。 |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | 構造化付加モードでの MaxiCode バーコード ID を取得します。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | 構造化付加モードでの MaxiCode バーコードの数を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode エンコードモードを設定します。 |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode エンコードモードを設定します。 |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | MaxiCode エンコードモードを設定します。 |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | 構造化付加モードで MaxiCode バーコード ID を設定します。 |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | 構造化付加モードで MaxiCode バーコードの数を設定します。 |
| [setMode(int value)](#setMode-int-) | MaxiCode エンコードモードを設定します。 |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | 構造化付加モードで MaxiCode バーコード ID を設定します。 |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | 構造化付加モードで MaxiCode バーコードの数を設定します。 |
| [toString()](#toString--) | この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D バーコードモジュールの高さ/幅比率。

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


ECI エンコーディングを取得します。 MaxiCodeEncodeMode が Auto の場合に使用されます。 デフォルト値: ISO-8859-1。

**Returns:**
int - ECI エンコーディング。
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


MaxiCode エンコードモードを取得します。 デフォルト値: Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


MaxiCode エンコードモードを取得します。 デフォルト値: Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


MaxiCode エンコードモードを取得します。

**Returns:**
int - MaxiCode エンコードモード。
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


構造化付加モードで MaxiCode バーコード ID を取得します。ID は 1 から 8 の間の値でなければなりません。デフォルト値: 0

**Returns:**
int - 構造化付加モードでの MaxiCode バーコード ID。
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


構造化付加モードで MaxiCode バーコードの数を取得します。カウント数は 2 から 8 の間の値でなければなりません（最大バーコード数）。デフォルト値: -1

**Returns:**
int - 構造化付加モードでの MaxiCode バーコードの数。
### getMode() {#getMode--}
```
public final int getMode()
```


MaxiCode エンコードモードを取得します。

**Returns:**
int - MaxiCode エンコードモード。
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


構造化付加モードで MaxiCode バーコード ID を取得します。ID は 1 から 8 の間の値でなければなりません。デフォルト値: 0

**Returns:**
int - 構造化付加モードでの MaxiCode バーコード ID。
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


構造化付加モードで MaxiCode バーコードの数を取得します。カウント数は 2 から 8 の間の値でなければなりません（最大バーコード数）。デフォルト値: -1

**Returns:**
int - 構造化付加モードでの MaxiCode バーコードの数。
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D バーコードモジュールの高さ/幅比率。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI エンコーディングを設定します。 MaxiCodeEncodeMode が Auto の場合に使用されます。 デフォルト値: ISO-8859-1。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | ECI エンコーディング。 |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode エンコードモードを設定します。 デフォルト値: Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode エンコードモード。 |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode エンコードモードを設定します。 デフォルト値: Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode エンコードモード。 |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


MaxiCode エンコードモードを設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | MaxiCode エンコードモード。 |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


構造化付加モードで MaxiCode バーコード ID を設定します。ID は 1 から 8 の間の値でなければなりません。デフォルト値: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | 構造化付加モードの MaxiCode バーコード ID。 |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


構造化付加モードで MaxiCode バーコードの数を設定します。カウント数は 2 から 8 の間の値でなければなりません（最大バーコード数）。デフォルト値: -1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | 構造化追加モードでの MaxiCode バーコードのカウント。 |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


MaxiCode エンコードモードを設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | MaxiCode エンコードモード。 |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


構造化付加モードで MaxiCode バーコード ID を設定します。ID は 1 から 8 の間の値でなければなりません。デフォルト値: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | 構造化付加モードの MaxiCode バーコード ID。 |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


構造化付加モードで MaxiCode バーコードの数を設定します。カウント数は 2 から 8 の間の値でなければなりません（最大バーコード数）。デフォルト値: -1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | 構造化追加モードでの MaxiCode バーコードのカウント。 |

### toString() {#toString--}
```
public String toString()
```


この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) を表す文字列。
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

