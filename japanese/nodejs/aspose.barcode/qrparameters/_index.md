---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "QR パラメータ。"
type: docs
weight: 830
url: /ja/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

QR パラメータ。

```js
new QrParameters()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D バーコードモジュールの高さ/幅比率 |
| [getECIEncoding()](#geteciencoding) | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | QR および RectMicroQR バーで GS1 の特殊文字をバイトモードでエンコードすべきかを示す値を取得または設定します |
| [getEncodeMode()](#getencodemode) | BarCode のエンコードモードの QR シンボルタイプです。デフォルト値: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LevelL、LevelM、LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | MicroQR コードのバージョンです。M1 バージョンから M4 バージョンまで。デフォルト値は MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [getQrEncodeMode()](#getqrencodemode) | BarCode のエンコードモードの QR シンボルタイプです。デフォルト値: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | QR / MicroQR セレクターモードです。標準 QR シンボルには ForceQR を、MicroQR には Auto を選択します。 |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | QR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。詳細は QRError を参照してください。 |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | QR コードのバージョンです。QR コードは Version1 から Version40、MicroQr は M1 から M4 まで。デフォルト値は QRVersion.AUT。 |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | RectMicroQR コードのバージョンです。R7x59 バージョンから R17x139 バージョンまで。デフォルト値は RectMicroQRVersion.Auto。 |
| [getStructuredAppend()](#getstructuredappend) | QR Structured Append パラメータ。 |
| [getVersion()](#getversion) | QR コードのバージョンです。Version1 から Version40 まで。デフォルト値は QRVersion.Auto。 |
| [setAspectRatio()](#setaspectratio) | 2D バーコードモジュールの高さ/幅比率 |
| [setECIEncoding()](#seteciencoding) | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | QR および RectMicroQR バーで GS1 の特殊文字をバイトモードでエンコードすべきかを示す値を取得または設定します |
| [setEncodeMode()](#setencodemode) | BarCode のエンコードモードの QR シンボルタイプです。デフォルト値: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LevelL、LevelM、LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | MicroQR コードのバージョンです。M1 バージョンから M4 バージョンまで。デフォルト値は MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | 拡張チャンネル解釈識別子です。使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。 |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | BarCode のエンコードモードの QR シンボルタイプです。デフォルト値: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | QR / MicroQR セレクターモードです。標準 QR シンボルには ForceQR を、MicroQR には Auto を選択します。 |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | QR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。詳細は QRError を参照してください。 |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | QR コードのバージョンです。QR コードは Version1 から Version40、MicroQr は M1 から M4 まで。デフォルト値は QRVersion.AUT。 |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | RectMicroQR コードのバージョンです。R7x59 バージョンから R17x139 バージョンまで。デフォルト値は RectMicroQRVersion.Auto。 |
| [setStructuredAppend()](#setstructuredappend) | QR Structured Append パラメータ。 |
| [setVersion()](#setversion) | QR コードのバージョンです。Version1 から Version40 まで。デフォルト値は QRVersion.Auto。 |
| [toString()](#tostring) | この QrParameters の人間が読める文字列表現を返します。 |

### getAspectRatio() {#getaspectratio}

2D バーコードモジュールの高さ/幅比率

### getECIEncoding() {#geteciencoding}

拡張チャネル解釈識別子です。シンボル内のデータをエンコードする際に使用された参照情報をバーコードリーダーに伝えるために使用されます。現在の実装はすべての既知の文字セットエンコーディングを含みます。MicroQR ではサポートされていません。

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかを示す値を取得または設定します。false の場合、QR 仕様に従い GS1 区切り文字は英数字モードで '%' としてエンコードされる可能性があります。true の場合、GS1 グループ区切り文字は 0x1D 文字としてバイトモードでエンコードされ、'%' 文字もデータとして保持するためにバイトモードでエンコードされます。このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダーとの互換性を向上させ、'%' データ文字が GS1 区切り文字として解釈されるのを防ぎます。

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

BarCode のエンコードモードの QR シンボルタイプです。デフォルト値: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

### getMicroQRVersion() {#getmicroqrversion}

MicroQR コードのバージョンです。M1 バージョンから M4 バージョンまで。デフォルト値は MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用される参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装はすべての既知の文字セットエンコーディングで構成されています。

### getQrEncodeMode() {#getqrencodemode}

BarCode のエンコードモードの QR シンボルタイプです。デフォルト値: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR セレクターモードです。標準 QR シンボルには ForceQR を、MicroQR には Auto を選択します。

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

QR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。QRErrorLevel を参照してください。

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

QR コードのバージョンです。QR コードは Version1 から Version40、MicroQr は M1 から M4 まで。デフォルト値は QRVersion.AUTO。

### getRectMicroQrVersion() {#getrectmicroqrversion}

RectMicroQR コードのバージョンです。R7x59 バージョンから R17x139 バージョンまで。デフォルト値は RectMicroQRVersion.Auto。

### getStructuredAppend() {#getstructuredappend}

QR Structured Append パラメータ。

### getVersion() {#getversion}

QR コードのバージョンです。Version1 から Version40 まで。デフォルト値は QRVersion.Auto。

### setAspectRatio() {#setaspectratio}

2D バーコードモジュールの高さ/幅比率

### setECIEncoding() {#seteciencoding}

拡張チャネル解釈識別子です。シンボル内のデータをエンコードする際に使用された参照情報をバーコードリーダーに伝えるために使用されます。現在の実装はすべての既知の文字セットエンコーディングを含みます。MicroQR ではサポートされていません。

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかを示す値を取得または設定します。false の場合、QR 仕様に従い GS1 区切り文字は英数字モードで '%' としてエンコードされる可能性があります。true の場合、GS1 グループ区切り文字は 0x1D 文字としてバイトモードでエンコードされ、'%' 文字もデータとして保持するためにバイトモードでエンコードされます。このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダーとの互換性を向上させ、'%' データ文字が GS1 区切り文字として解釈されるのを防ぎます。

| パラメータ | 説明 |
| --- | --- |
| 値 | QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかを示す値。 |

### setEncodeMode() {#setencodemode}

BarCode のエンコードモードの QR シンボルタイプです。デフォルト値: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。

### setMicroQRVersion() {#setmicroqrversion}

MicroQR コードのバージョンです。M1 バージョンから M4 バージョンまで。デフォルト値は MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

拡張チャネル解釈識別子。シンボル内のデータをエンコードする際に使用される参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装はすべての既知の文字セットエンコーディングで構成されています。

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

BarCode のエンコードモードの QR シンボルタイプです。デフォルト値: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR セレクターモードです。標準 QR シンボルには ForceQR を、MicroQR には Auto を選択します。

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

QR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。QRErrorLevel を参照してください。

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

QR コードのバージョンです。QR コードは Version1 から Version40、MicroQr は M1 から M4 まで。デフォルト値は QRVersion.AUTO。

### setRectMicroQrVersion() {#setrectmicroqrversion}

RectMicroQR コードのバージョンです。R7x59 バージョンから R17x139 バージョンまで。デフォルト値は RectMicroQRVersion.Auto。

### setStructuredAppend() {#setstructuredappend}

QR Structured Append パラメータ。

### setVersion() {#setversion}

QR コードのバージョンです。Version1 から Version40 まで。デフォルト値は QRVersion.Auto。

### toString() {#tostring}

この QrParameters の人間が読める文字列表現を返します。

**Returns:** A string that represents this QrParameters.
