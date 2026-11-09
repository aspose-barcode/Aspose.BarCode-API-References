---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "DataMatrix パラメータ。"
type: docs
weight: 32
url: /ja/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix パラメータ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率です。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEccType()](#getEccType--) | Datamatrix の ECC タイプを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix バーコードのエンコードモードです。 |
| [getMacroCharacters()](#getMacroCharacters--) | マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコードを取得するために使用されます。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | DataMatrixバーコードの構造化付加モード用バーコードID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix バーコードの Structured Append モードのバーコード数。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix バーコードの Structured Append モードのファイル ID。 |
| [getVersion()](#getVersion--) | Datamatrix シンボルサイズを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率です。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix の ECC タイプを設定します。 |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix バーコードのエンコードモードです。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコードを取得するために使用されます。 |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | DataMatrixバーコードの構造化付加モード用バーコードID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Datamatrix バーコードの Structured Append モードのバーコード数。 |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datamatrix バーコードの Structured Append モードのファイル ID。 |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Datamatrix シンボルサイズを設定します。 |
| [toString()](#toString--) | この [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) の人間が読める文字列表現を返します。 |
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


ECI エンコーディングを取得します。EncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1

**Returns:**
int - ECI エンコーディング。
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Datamatrix の ECC タイプを取得します。デフォルト値: DataMatrixEccType.Ecc200。

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Datamatrix バーコードのエンコードモードです。デフォルト値: EncodeMode.Auto。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコーディングを取得するために使用されます。DataMatrixEccType.Ecc200 または DataMatrixEccType.EccAuto と組み合わせてのみ使用可能です。EncodeTypes.GS1DataMatrix では使用できません。デフォルト値: MacroCharacters.None。

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Datamatrix バーコードの Structured Append モードのバーコード ID。デフォルト値: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Datamatrix バーコードの Structured Append モードのバーコード数。デフォルト値: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datamatrix バーコードの Structured Append モードのファイル ID。デフォルト値: 0

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
public final int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


シンボル内に含まれるデータをリーダー初期化用のプログラムとして解釈するようリーダーに指示するために使用されます。デフォルト値: false

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


2D バーコードモジュールの高さ/幅比率です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI エンコーディングを設定します。EncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | ECI エンコーディング。 |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Datamatrix の ECC タイプを設定します。デフォルト値: DataMatrixEccType.Ecc200。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | Datamatrix の ECC タイプです。 |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix バーコードのエンコードモードです。デフォルト値: EncodeMode.Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコーディングを取得するために使用されます。DataMatrixEccType.Ecc200 または DataMatrixEccType.EccAuto と組み合わせてのみ使用可能です。EncodeTypes.GS1DataMatrix では使用できません。デフォルト値: MacroCharacters.None。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


シンボル内に含まれるデータをリーダー初期化用のプログラムとして解釈するようリーダーに指示するために使用されます。デフォルト値: false

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix バーコードの Structured Append モードのバーコード ID。デフォルト値: 0

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix バーコードの Structured Append モードのバーコード数。デフォルト値: 0

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix バーコードの Structured Append モードのファイル ID。デフォルト値: 0

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Datamatrix シンボルサイズを設定します。デフォルト値: Version.Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | Datamatrix シンボルサイズ。 |

### toString() {#toString--}
```
public String toString()
```


この [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) を表す文字列です。
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

