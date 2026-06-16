---
title: AztecParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Aztec parameters.
type: docs
weight: 12
url: /ja/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率。 |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Aztec のエンコードモードを取得します。 |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Aztec タイプのバーコードのエラー訂正レベル。 |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Aztec シンボルモードを取得します。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | Aztec のエンコードモードを取得します。 |
| [getErrorLevel()](#getErrorLevel--) | Aztec タイプのバーコードのエラー訂正レベル。 |
| [getLayersCount()](#getLayersCount--) | Aztec シンボルのレイヤー数を取得します。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztecバーコードの構造付加モードのバーコードID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztecバーコードの構造付加モードのバーコード数。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztecバーコードの構造付加モードのファイルID（オプションフィールド）。 |
| [getSymbolMode()](#getSymbolMode--) | Aztec シンボルモードを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率。 |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Aztecエンコードモードを設定します。 |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Aztec タイプのバーコードのエラー訂正レベル。 |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Aztecシンボルモードを設定します。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Aztecエンコードモードを設定します。 |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec タイプのバーコードのエラー訂正レベル。 |
| [setLayersCount(int value)](#setLayersCount-int-) | Aztecシンボルの層数を設定します。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztecバーコードの構造付加モードのバーコードID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztecバーコードの構造付加モードのバーコード数。 |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztecバーコードの構造付加モードのファイルID（オプションフィールド）。 |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Aztecシンボルモードを設定します。 |
| [toString()](#toString--) | この [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) の人間が読める文字列表現を返します。 |
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
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


Aztecエンコードモードを取得します。デフォルト値: Auto。

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - Aztecエンコードモード。
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Aztecタイプのバーコードの誤り訂正レベル。値は5から95の間である必要があります。

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


Aztecシンボルモードを取得します。デフォルト値: AztecSymbolMode.Auto。

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


ECIエンコーディングを取得します。AztecEncodeModeがAutoのときに使用されます。デフォルト値: ISO-8859-1。

**Returns:**
int - ECI エンコーディング。
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Aztecエンコードモードを取得します。デフォルト値: Auto。

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - Aztecエンコードモード。
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Aztecタイプのバーコードの誤り訂正レベル。値は5から95の間である必要があります。

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Aztecシンボルの層数を取得します。コンパクトモードでは層数は1から3の範囲、フルレンジモードでは1から32の範囲である必要があります。デフォルト値: 0（自動）。

**Returns:**
int - Aztecシンボルの層数。
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Aztecバーコードの構造付加モードのバーコードID。バーコードIDは1からバーコード数の範囲である必要があります。デフォルト値: 0。

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztecバーコードの構造付加モードのバーコード数。バーコード数は1から26の範囲である必要があります。デフォルト値: 0。

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztecバーコードの構造付加モードのファイルID（オプションフィールド）。ファイルIDにスペースを含めてはいけません。デフォルト値: 空文字列。

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Aztecシンボルモードを取得します。デフォルト値: AztecSymbolMode.Auto。

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。

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

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


Aztecエンコードモードを設定します。デフォルト値: Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | com.aspose.barcode.generation.AztecEncodeMode | Aztecエンコードモード。 |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Aztecタイプのバーコードの誤り訂正レベル。値は5から95の間である必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


Aztecシンボルモードを設定します。デフォルト値: AztecSymbolMode.Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | Aztecシンボルモード。 |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECIエンコーディングを設定します。AztecEncodeModeがAutoのときに使用されます。デフォルト値: ISO-8859-1。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | ECI エンコーディング。 |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Aztecエンコードモードを設定します。デフォルト値: Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | com.aspose.barcode.generation.AztecEncodeMode | Aztecエンコードモード。 |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Aztecタイプのバーコードの誤り訂正レベル。値は5から95の間である必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Aztecシンボルの層数を設定します。コンパクトモードでは層数は1から3の範囲、フルレンジモードでは1から32の範囲である必要があります。デフォルト値: 0（自動）。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | Aztecシンボルの層数。 |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


シンボル内に含まれるデータをリーダーの初期化用プログラムとして解釈するようリーダーに指示するために使用されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Aztecバーコードの構造付加モードのバーコードID。バーコードIDは1からバーコード数の範囲である必要があります。デフォルト値: 0。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztecバーコードの構造付加モードのバーコード数。バーコード数は1から26の範囲である必要があります。デフォルト値: 0。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztecバーコードの構造付加モードのファイルID（オプションフィールド）。ファイルIDにスペースを含めてはいけません。デフォルト値: 空文字列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Aztecシンボルモードを設定します。デフォルト値: AztecSymbolMode.Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | Aztecシンボルモード。 |

### toString() {#toString--}
```
public String toString()
```


この [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) を表す文字列です。
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

