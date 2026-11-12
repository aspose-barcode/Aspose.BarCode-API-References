---
title: "SwissQRCodetext"
linktitle: "SwissQRCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "SwissQR コードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 930
url: /ja/nodejs/aspose.barcode/swissqrcodetext/
---

## SwissQRCodetext class

SwissQR コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```js
new SwissQRCodetext(bill)
```

SwissQRCodetext のインスタンスを作成します。

| パラメータ | 説明 |
| --- | --- |
| 請求書 | SwissQR 請求書データ |

**Throws:** BarcodeException

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | バーコードのタイプを取得します。 |
| [getBill()](#getbill) | SwissQR 請求書データ |
| [getConstructedCodetext()](#getconstructedcodetext) | SwissQR 請求書データからコードテキストを構築します |
| [initFromString(constructedCodetext)](#initfromstring) | 構築されたコードテキストで Bill を初期化します。 |

### getBarcodeType() {#getbarcodetype}

バーコードのタイプを取得します。

**Returns:** Barcode type.

### getBill() {#getbill}

SwissQR 請求書データ

### getConstructedCodetext() {#getconstructedcodetext}

SwissQR 請求書データからコードテキストを構築します

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

構築されたコードテキストで Bill を初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |
