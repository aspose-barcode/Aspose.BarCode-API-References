---
title: "DotCodeParameters"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "DotCode パラメータ。"
type: docs
weight: 35
url: /ja/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode パラメータ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2Dバーコードモジュールの高さ/幅比率。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数を識別します。 |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを識別します。 |
| [getEncodeMode()](#getEncodeMode--) | DotCode エンコードモードを識別します。 |
| [getRows()](#getRows--) | 行数を識別します。 |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | DotCode 構造付加モードバーコードの ID を識別します。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | DotCode 構造付加モードバーコードの数を識別します。 |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | コードが、バーコードリーダーの初期化または再プログラミングの指示として、以下のデータを解釈させるために使用されるかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2Dバーコードモジュールの高さ/幅比率。 |
| [setColumns(int value)](#setColumns-int-) | 列数を識別します。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを識別します。 |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | DotCode エンコードモードを識別します。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | コードが、バーコードリーダーの初期化または再プログラミングの指示として、以下のデータを解釈させるために使用されるかどうかを示します。 |
| [setRows(int value)](#setRows-int-) | 行数を識別します。 |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | DotCode 構造付加モードバーコードの ID を識別します。 |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | DotCode 構造付加モードバーコードの数を識別します。 |
| [toString()](#toString--) | この [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) の人間が読みやすい文字列表現を返します。 |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


列数を識別します。DotCode シンボルの行数と列数の合計は奇数でなければなりません。列数は最低 5 である必要があります。デフォルト値: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI エンコーディングを識別します。DotCodeEncodeMode が Auto のときに使用されます。デフォルト値: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


DotCode エンコードモードを識別します。デフォルト値: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


行数を識別します。DotCode シンボルの行数と列数の合計は奇数でなければなりません。行数は最低 5 である必要があります。デフォルト値: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode 構造付加モードバーコードの ID を識別します。ID は 1 から開始し、バーコード数以下でなければなりません。デフォルト値は -1 です。

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode 構造付加モードバーコードの数を識別します。デフォルト値は -1 です。カウントは 1 から 35 の範囲でなければなりません。

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


コードが、バーコードリーダーの初期化または再プログラミングの指示として、以下のデータを解釈させるために使用されるかどうかを示します。デフォルト値は false です。

**Returns:**
boolean
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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


列数を識別します。DotCode シンボルの行数と列数の合計は奇数でなければなりません。列数は最低 5 である必要があります。デフォルト値: -1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI エンコーディングを識別します。DotCodeEncodeMode が Auto のときに使用されます。デフォルト値: ISO-8859-1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


DotCode エンコードモードを識別します。デフォルト値: Auto.

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


コードが、バーコードリーダーの初期化または再プログラミングの指示として、以下のデータを解釈させるために使用されるかどうかを示します。デフォルト値は false です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


行数を識別します。DotCode シンボルの行数と列数の合計は奇数でなければなりません。行数は最低 5 である必要があります。デフォルト値: -1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


DotCode 構造付加モードバーコードの ID を識別します。ID は 1 から開始し、バーコード数以下でなければなりません。デフォルト値は -1 です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


DotCode 構造付加モードバーコードの数を識別します。デフォルト値は -1 です。カウントは 1 から 35 の範囲でなければなりません。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```


この [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) を表す文字列です。
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

