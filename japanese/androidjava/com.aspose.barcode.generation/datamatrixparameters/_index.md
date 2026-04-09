---
title: DataMatrixParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: DataMatrix parameters.
type: docs
weight: 34
url: /ja/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数。 |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Datamatrix ECC タイプを取得します。 |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Datamatrix シンボルサイズを取得します。 |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEccType()](#getEccType--) | Datamatrix ECC タイプを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを取得するために使用されます。 |
| [getRows()](#getRows--) | 行数。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Datamatrix バーコードの Structured Append モード用バーコード ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix バーコードの Structured Append モード用バーコード数。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix バーコードの Structured Append モード用ファイル ID。 |
| [getVersion()](#getVersion--) | Datamatrix シンボルサイズを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率。 |
| [setColumns(int value)](#setColumns-int-) | 列数。 |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC タイプを設定します。 |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Datamatrix シンボルサイズを設定します。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix ECC タイプを設定します。 |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコードを取得するために使用されます。 |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。 |
| [setRows(int value)](#setRows-int-) | 行数。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Datamatrix バーコードの Structured Append モード用バーコード ID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Datamatrix バーコードの Structured Append モード用バーコード数。 |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datamatrix バーコードの Structured Append モード用ファイル ID。 |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Datamatrix シンボルサイズを設定します。 |
| [toString()](#toString--) | この [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) の人間が読みやすい文字列表現を返します。 |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


列数。

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Datamatrix ECC タイプを取得します。デフォルト値: DataMatrixEccType.Ecc200。

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Datamatrix バーコードのエンコードモード。デフォルト値: EncodeMode.Auto。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Datamatrix シンボルサイズを取得します。デフォルト値: Version.Auto。

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI エンコーディングを取得します。EncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1。

**Returns:**
int - ECI エンコーディング。
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Datamatrix ECC タイプを取得します。デフォルト値: DataMatrixEccType.Ecc200。

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Datamatrix バーコードのエンコードモード。デフォルト値: EncodeMode.Auto。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコーディングを取得するために使用されます。DataMatrixEccType.Ecc200 または DataMatrixEccType.EccAuto と併用可能です。EncodeTypes.GS1DataMatrix では使用できません。デフォルト値: MacroCharacters.None。

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


行数。

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Datamatrix バーコードの Structured Append モード用バーコード ID。デフォルト値: 0。

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Datamatrix バーコードの Structured Append モード用バーコード数。デフォルト値: 0。

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datamatrix バーコードの Structured Append モード用ファイル ID。デフォルト値: 0。

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Datamatrix シンボルサイズを取得します。デフォルト値: Version.Auto。

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


シンボル内のデータをリーダー初期化用プログラミングとして解釈するようリーダーに指示するために使用されます。デフォルト値: false。

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


2D バーコードモジュールの高さ/幅比率。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


列数。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Datamatrix ECC タイプを設定します。デフォルト値: DataMatrixEccType.Ecc200。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | Datamatrix ECC タイプ。 |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix バーコードのエンコードモード。デフォルト値: EncodeMode.Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Datamatrix シンボルサイズを設定します。デフォルト値: Version.Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | Datamatrix シンボルサイズ。 |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI エンコーディングを設定します。EncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | ECI エンコーディング。 |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Datamatrix ECC タイプを設定します。デフォルト値: DataMatrixEccType.Ecc200。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | Datamatrix ECC タイプ。 |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix バーコードのエンコードモード。デフォルト値: EncodeMode.Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコーディングを取得するために使用されます。DataMatrixEccType.Ecc200 または DataMatrixEccType.EccAuto と併用可能です。EncodeTypes.GS1DataMatrix では使用できません。デフォルト値: MacroCharacters.None。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


シンボル内のデータをリーダー初期化用プログラミングとして解釈するようリーダーに指示するために使用されます。デフォルト値: false。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


行数。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix バーコードの Structured Append モード用バーコード ID。デフォルト値: 0。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix バーコードの Structured Append モード用バーコード数。デフォルト値: 0。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix バーコードの Structured Append モード用ファイル ID。デフォルト値: 0。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Datamatrix シンボルサイズを設定します。デフォルト値: Version.Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | Datamatrix シンボルサイズ。 |

### toString() {#toString--}
```
public String toString()
```


この [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) を表す文字列。
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

