---
title: "AztecParametersUI"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "AztecParameters クラスの UI ラッパー"
type: docs
weight: 10
url: /ja/java/com.aspose.barcode.barcodecontrol/aztecparametersui/
---
**Inheritance:**
java.lang.Object
```
public class AztecParametersUI
```

AztecParameters クラスの UI ラッパー
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率です。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI エンコーディングを取得します。 |
| [getEncodeMode()](#getEncodeMode--) | Aztec エンコードモードを取得します。 |
| [getErrorLevel()](#getErrorLevel--) | Aztec タイプのバーコードの誤り訂正レベルです。 |
| [getLayersCount()](#getLayersCount--) | Aztec シンボルのレイヤー数を取得します。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec バーコードの Structured Append モード用のバーコード ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec バーコードの Structured Append モード用のバーコード数。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec バーコードの Structured Append モード用のファイル ID（オプションフィールド）。 |
| [getSymbolMode()](#getSymbolMode--) | Aztec シンボルモードを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率です。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI エンコーディングを設定します。 |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Aztec エンコードモードを設定します。 |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec タイプのバーコードの誤り訂正レベルです。 |
| [setLayersCount(int value)](#setLayersCount-int-) | Aztec シンボルのレイヤー数を設定します。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | シンボル内のデータをリーダー初期化用のプログラミングとして解釈するようリーダーに指示するために使用されます。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztec バーコードの Structured Append モード用のバーコード ID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztec バーコードの Structured Append モード用のバーコード数。 |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztec バーコードの Structured Append モード用のファイル ID（オプションフィールド）。 |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Aztec シンボルモードを設定します。 |
| [toString()](#toString--) | この [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) の人間が読みやすい文字列表現を返します。 |
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
public float getAspectRatio()
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


ECI エンコーディングを取得します。AztecEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1。

**Returns:**
int - ECI エンコーディング。
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Aztec エンコードモードを取得します。デフォルト値: Auto。

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - Aztec エンコードモードです。
### getErrorLevel() {#getErrorLevel--}
```
public int getErrorLevel()
```


Aztec タイプのバーコードの誤り訂正レベル。値は 10 から 95 の間である必要があります。

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Aztec シンボルのレイヤー数を取得します。コンパクトモードでは 1 から 3、フルレンジモードでは 1 から 32 の範囲である必要があります。デフォルト値: 0（自動）。

**Returns:**
int - Aztec シンボルのレイヤー数。
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Aztec バーコードの Structured Append モード用のバーコード ID。バーコード ID は 1 からバーコード数までの範囲である必要があります。デフォルト値: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztec バーコードの Structured Append モード用のバーコード数。バーコード数は 1 から 26 の範囲である必要があります。デフォルト値: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztec バーコードの Structured Append モード用のファイル ID（オプションフィールド）。ファイル ID にスペースを含めてはいけません。デフォルト値: 空文字列

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public AztecSymbolMode getSymbolMode()
```


Aztec シンボルモードを取得します。

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode)
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
public void setAspectRatio(float value)
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


ECI エンコーディングを設定します。AztecEncodeMode が Auto のときに使用されます。デフォルト値: ISO-8859-1

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | ECI エンコーディング。 |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Aztec エンコードモードを設定します。デフォルト値: Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.barcode.generation.AztecEncodeMode | Aztec エンコードモードです。 |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public void setErrorLevel(int value)
```


Aztec タイプのバーコードの誤り訂正レベル。値は 10 から 95 の間である必要があります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Aztec シンボルのレイヤー数を設定します。コンパクトモードでは 1 から 3、フルレンジモードでは 1 から 32 の範囲である必要があります。デフォルト値: 0（自動）。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | Aztec シンボルのレイヤー数。 |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
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


Aztec バーコードの Structured Append モード用のバーコード ID。バーコード ID は 1 からバーコード数までの範囲である必要があります。デフォルト値: 0

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztec バーコードの Structured Append モード用のバーコード数。バーコード数は 1 から 26 の範囲である必要があります。デフォルト値: 0

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztec バーコードの Structured Append モード用のファイル ID（オプションフィールド）。ファイル ID にスペースを含めてはいけません。デフォルト値: 空文字列

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public void setSymbolMode(AztecSymbolMode value)
```


Aztec シンボルモードを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) |  |

### toString() {#toString--}
```
public String toString()
```


この [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) を表す文字列です。
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

