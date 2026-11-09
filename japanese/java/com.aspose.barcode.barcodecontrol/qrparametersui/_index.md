---
title: "QrParametersUI"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "UI ラッパー for com.aspose.barcode.generation.QrParameters クラス。"
type: docs
weight: 17
url: /ja/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

UI ラッパー for com.aspose.barcode.generation.QrParameters クラス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D バーコードモジュールの高さ/幅比率です。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 拡張チャネル解釈識別子。 |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかどうかを示す値を取得または設定します。 |
| [getEncodeMode()](#getEncodeMode--) | BarCode のエンコーディングモードの QR シンボロジータイプ。 |
| [getErrorLevel()](#getErrorLevel--) | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。 |
| [getMicroQrVersion()](#getMicroQrVersion--) | MicroQR コードのバージョン。 |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR コードのバージョン。 |
| [getVersion()](#getVersion--) | QR コードのバージョン。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D バーコードモジュールの高さ/幅比率です。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 拡張チャネル解釈識別子。 |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかどうかを示す値を取得または設定します。 |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | BarCode のエンコーディングモードの QR シンボロジータイプ。 |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。 |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR コードのバージョン。 |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR コードのバージョン。 |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR コードのバージョン。 |
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
public int getECIEncoding()
```


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべてのよく知られた文字セットエンコーディングを含みます。MicroQR ではサポートされていません。

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかどうかを示す値を取得または設定します。

false の場合、QR 仕様に従い、アルファベット数字モードで GS1 区切り文字が '%' としてエンコードされる可能性があります。

true の場合、GS1 グループ区切り文字はバイトモードで 0x1D 文字としてエンコードされ、'%' 文字もデータとして保持するためにバイトモードでエンコードされます。

このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダーとの互換性を向上させ、'%' データ文字が GS1 区切り文字として解釈されるのを防止します。

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


BarCode のエンコーディングモードの QR シンボロジータイプ。デフォルト値: QREncodeMode.Auto。

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
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
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


QR コードのバージョン。QR コードは Version1 から Version40、MicroQr は M1 から M4 まで。デフォルト値は QRVersion.Auto です。

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


2D バーコードモジュールの高さ/幅比率です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべてのよく知られた文字セットエンコーディングを含みます。MicroQR ではサポートされていません。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかどうかを示す値を取得または設定します。

false の場合、QR 仕様に従い、アルファベット数字モードで GS1 区切り文字が '%' としてエンコードされる可能性があります。

true の場合、GS1 グループ区切り文字はバイトモードで 0x1D 文字としてエンコードされ、'%' 文字もデータとして保持するためにバイトモードでエンコードされます。

このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダーとの互換性を向上させ、'%' データ文字が GS1 区切り文字として解釈されるのを防止します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


BarCode のエンコーディングモードの QR シンボロジータイプ。デフォルト値: QREncodeMode.Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
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

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR コードのバージョン。QR コードは Version1 から Version40、MicroQr は M1 から M4 まで。デフォルト値は QRVersion.Auto です。

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

