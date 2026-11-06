---
title: "QrParameters"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "QR パラメータ。"
type: docs
weight: 62
url: /ja/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR パラメータ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2Dバーコードモジュールの高さ/幅比率。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 拡張チャネル解釈識別子。 |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | QR シンボロジータイプは BarCode のエンコードモードです。 |
| [getErrorLevel()](#getErrorLevel--) | QR、MicroQR、RectMicroQR バーコードの Reed‑Solomon 誤り訂正レベル。 |
| [getMicroQRVersion()](#getMicroQRVersion--) | MicroQR Code のバージョン。 |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR Code のバージョン。 |
| [getStructuredAppend()](#getStructuredAppend--) | QR 構造化追加パラメータ。 |
| [getVersion()](#getVersion--) | QR コードのバージョン。Version1 から Version40 まで。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2Dバーコードモジュールの高さ/幅比率。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 拡張チャネル解釈識別子。 |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR シンボロジータイプは BarCode のエンコードモードです。 |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR、MicroQR、RectMicroQR バーコードの Reed‑Solomon 誤り訂正レベル。 |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR Code のバージョン。 |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR Code のバージョン。 |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR 構造化追加パラメータ。 |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR コードのバージョン。Version1 から Version40 まで。 |
| [toString()](#toString--) | この [QrParameters](../../com.aspose.barcode.generation/qrparameters) の人間が読みやすい文字列表現を返します。 |
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


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべてのよく知られた文字セットエンコーディングで構成されています。MicroQR ではサポートされていません。

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかどうかを示す値を取得または設定します。

false の場合、QR 仕様に従い、GS1 区切り文字は英数字モードで '%' としてエンコードされる可能性があります。

true の場合、GS1 グループ区切り文字はバイトモードで 0x1D 文字としてエンコードされ、'%' 文字もデータとして保持するためにバイトモードでエンコードされます。

このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダーとの互換性を向上させ、'%' データ文字が GS1 区切り文字として解釈されるのを防止します。

**Returns:**
boolean - QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかどうかを示す値。
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


QR シンボロジータイプは BarCode のエンコードモードです。デフォルト値: QREncodeMode.Auto。

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR、MicroQR、RectMicroQR バーコードの Reed‑Solomon 誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


MicroQR コードのバージョン。M1 バージョンから M4 バージョンまで。デフォルト値は MicroQRVersion.Auto です。

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR コードのバージョン。R7x59 バージョンから R17x139 バージョンまで。デフォルト値は RectMicroQRVersion.Auto です。

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


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべてのよく知られた文字セットエンコーディングで構成されています。MicroQR ではサポートされていません。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかどうかを示す値を取得または設定します。

false の場合、QR 仕様に従い、GS1 区切り文字は英数字モードで '%' としてエンコードされる可能性があります。

true の場合、GS1 グループ区切り文字はバイトモードで 0x1D 文字としてエンコードされ、'%' 文字もデータとして保持するためにバイトモードでエンコードされます。

このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダーとの互換性を向上させ、'%' データ文字が GS1 区切り文字として解釈されるのを防止します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかどうかを示す値。 |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


QR シンボロジータイプは BarCode のエンコードモードです。デフォルト値: QREncodeMode.Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR、MicroQR、RectMicroQR バーコードの Reed‑Solomon 誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


MicroQR コードのバージョン。M1 バージョンから M4 バージョンまで。デフォルト値は MicroQRVersion.Auto です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR コードのバージョン。R7x59 バージョンから R17x139 バージョンまで。デフォルト値は RectMicroQRVersion.Auto です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR 構造化付加パラメータ。構造化付加モードは MicroQR および RectMicroQR バーコードではサポートされていません。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR コードのバージョン。Version1 から Version40 まで。デフォルト値は QRVersion.Auto です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


この [QrParameters](../../com.aspose.barcode.generation/qrparameters) の人間が読みやすい文字列表現を返します。

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

