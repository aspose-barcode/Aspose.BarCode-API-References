---
title: QrParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: QR パラメータ。
type: docs
weight: 64
url: /ja/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR パラメータ。
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getEncodeMode()](#getEncodeMode--) | バーコードのエンコーディングモードの QR シンボロジータイプ。 |
| [getErrorLevel()](#getErrorLevel--) | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。 |
| [getMicroQRVersion()](#getMicroQRVersion--) | MicroQR Code のバージョン。 |
| [getQrECIEncoding()](#getQrECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getQrEncodeMode()](#getQrEncodeMode--) | バーコードのエンコーディングモードの QR シンボロジータイプ。 |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR セレクターモード。 |
| [getQrErrorLevel()](#getQrErrorLevel--) | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。 |
| [getQrVersion()](#getQrVersion--) | QR コードのバージョン。Version1 から Version40 まで。 |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR Code のバージョン。 |
| [getStructuredAppend()](#getStructuredAppend--) | QR 構造化追加パラメータ。 |
| [getVersion()](#getVersion--) | QR コードのバージョン。Version1 から Version40 まで。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | バーコードのエンコーディングモードの QR シンボロジータイプ。 |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。 |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR Code のバージョン。 |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR セレクターモード。 |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR Code のバージョン。 |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR 構造化追加パラメータ。 |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR コードのバージョン。Version1 から Version40 まで。 |
| [toString()](#toString--) | この [QrParameters](../../com.aspose.barcode.generation/qrparameters) の人間が読める文字列表現を返します。 |
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


拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべての一般的な文字セットエンコーディングを含みます。MicroQR ではサポートされていません。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


バーコードのエンコーディングモードの QR シンボロジータイプ。デフォルト値: QREncodeMode.Auto。

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


MicroQR コードのバージョン。バージョン M1 から M4 まで。デフォルト値は MicroQRVersion.Auto です。

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべての一般的な文字セットエンコーディングを含みます。MicroQR ではサポートされていません。

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


バーコードのエンコーディングモードの QR シンボロジータイプ。デフォルト値: QREncodeMode.Auto。

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


QR / MicroQR セレクターモード。標準 QR シンボルには ForceQR を、MicroQR には Auto を選択します。

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


QR コードのバージョン。Version1 から Version40 まで。デフォルト値は QRVersion.Auto です。

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR コードのバージョン。バージョン R7x59 から R17x139 まで。デフォルト値は RectMicroQRVersion.Auto です。

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR 構造化付加パラメータ。構造化付加モードは MicroQR および RectMicroQR バーコードではサポートされていません。

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


QR コードのバージョン。Version1 から Version40 まで。デフォルト値は QRVersion.Auto です。

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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


拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべての一般的な文字セットエンコーディングを含みます。MicroQR ではサポートされていません。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


バーコードのエンコーディングモードの QR シンボロジータイプ。デフォルト値: QREncodeMode.Auto。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


MicroQR コードのバージョン。バージョン M1 から M4 まで。デフォルト値は MicroQRVersion.Auto です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


QR / MicroQR セレクターモード。標準 QR シンボルには ForceQR を、MicroQR には Auto を選択します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR コードのバージョン。バージョン R7x59 から R17x139 まで。デフォルト値は RectMicroQRVersion.Auto です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR 構造化付加パラメータ。構造化付加モードは MicroQR および RectMicroQR バーコードではサポートされていません。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR コードのバージョン。Version1 から Version40 まで。デフォルト値は QRVersion.Auto です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


この [QrParameters](../../com.aspose.barcode.generation/qrparameters) の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この [QrParameters](../../com.aspose.barcode.generation/qrparameters) を表す文字列です。
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

