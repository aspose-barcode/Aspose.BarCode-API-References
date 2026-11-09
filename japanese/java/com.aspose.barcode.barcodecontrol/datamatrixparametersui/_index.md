---
title: "DataMatrixParametersUI"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "UI ラッパー for com.aspose.barcode.generation.DataMatrixParameters クラス。"
type: docs
weight: 14
url: /ja/java/com.aspose.barcode.barcodecontrol/datamatrixparametersui/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParametersUI
```

UI ラッパー for com.aspose.barcode.generation.DataMatrixParameters クラス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率です。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEccType()](#getEccType--) | Datamatrix の ECC タイプを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix バーコードのエンコードモードです。 |
| [getMacroCharacters()](#getMacroCharacters--) | 最初の位置にあるマクロ文字のプロトコル（ECC 200 のみ） |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | 構造化追加モード用のバーコード IDです。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | 構造化追加モードのバーコード数です。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | 構造化追加モード用のファイル IDです。 |
| [getVersion()](#getVersion--) | DataMatrix シンボルのサイズです。 |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率です。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Datamatrix の ECC タイプを設定します。 |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix バーコードのエンコードモードです。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | 最初の位置にあるマクロ文字のプロトコル（ECC 200 のみ） |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | 構造化追加モード用のバーコード IDです。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | 構造化追加モードのバーコード数です。 |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | 構造化追加モード用のファイル IDです。 |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | DataMatrix シンボルのサイズです。 |
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


ECI エンコーディングを取得します。EncodeMode が Auto のときに使用されます。

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


最初の位置にあるマクロ文字のプロトコル（ECC 200 のみ）

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


構造化追加モード用のバーコード IDです。

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


構造化追加モードのバーコード数です。

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


構造化追加モード用のファイル IDです。

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


DataMatrix シンボルのサイズです。

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
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


シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。

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


ECI エンコーディングを設定します。EncodeMode が Auto のときに使用されます。

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


最初の位置にあるマクロ文字のプロトコル（ECC 200 のみ）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


構造化追加モード用のバーコード IDです。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


構造化追加モードのバーコード数です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


構造化追加モード用のファイル IDです。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


DataMatrix シンボルのサイズです。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

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

