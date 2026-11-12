---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "4 状態 Royal Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 580
url: /ja/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

4 状態 Royal Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```js
new MailmarkCodetext()
```

`MailmarkCodetext` クラスの新しいインスタンスを初期化します。

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | バーコードのタイプを取得します。 |
| [getClass_()](#getclass-) | "0" - Null または Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Mailmark データからコードテキストを構築します。 |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | PC と DP は PAF 形式に準拠する必要があります。国際的な "XY11 " を示す 9 文字の文字列（末尾の 5 つのスペースに注意） |
| [getFormat()](#getformat) | "0" – Null または Test "1" – Letter "2" – Large Letter |
| [getItemID()](#getitemid) | 最大値は 99999999 です。 |
| [getSupplychainID()](#getsupplychainid) | Barcode C の最大値は 99、Barcode L の最大値は 999999 です。 |
| [getVersionID()](#getversionid) | 現在 "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |
| [initFromString(constructedCodetext)](#initfromstring) | 構築されたコードテキストから Mailmark データを初期化します。 |
| [setClass_()](#setclass-) | "0" - Null または Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | PC と DP は PAF 形式に準拠する必要があります。国際的な "XY11 " を示す 9 文字の文字列（末尾の 5 つのスペースに注意） |
| [setFormat()](#setformat) | "0" – Null または Test "1" – LetterN "2" – Large Letter |
| [setItemID()](#setitemid) | 最大値は 99999999 です。 |
| [setSupplychainID()](#setsupplychainid) | Barcode C の最大値は 99、Barcode L の最大値は 999999 です。 |
| [setVersionID()](#setversionid) | 現在 "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |

### getBarcodeType() {#getbarcodetype}

バーコードのタイプを取得します。

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Null または Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

Mailmark データからコードテキストを構築します。

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

PC と DP は PAF 形式に準拠する必要があります。国際的な "XY11 " を示す 9 文字の文字列（末尾の 5 スペースに注意）または国内の仕分けコードを示す文字パターンです。国内の仕分けコードは外部郵便番号、内部郵便番号、そして配達ポイントサフィックスで構成されます。

### getFormat() {#getformat}

"0" – Null または Test "1" – Letter "2" – Large Letter

### getItemID() {#getitemid}

最大値は 99999999 です。

### getSupplychainID() {#getsupplychainid}

Barcode C の最大値は 99、Barcode L の最大値は 999999 です。

### getVersionID() {#getversionid}

現在 "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use)

### initFromString(constructedCodetext) {#initfromstring}

構築されたコードテキストから Mailmark データを初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |

### setClass_() {#setclass-}

"0" - Null または Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

PC と DP は PAF 形式に準拠する必要があります。国際的な "XY11 " を示す 9 文字の文字列（末尾の 5 スペースに注意）または国内の仕分けコードを示す文字パターンです。国内の仕分けコードは外部郵便番号、内部郵便番号、そして配達ポイントサフィックスで構成されます。

### setFormat() {#setformat}

"0" – Null または Test "1" – LetterN "2" – Large Letter

### setItemID() {#setitemid}

最大値は 99999999 です。

### setSupplychainID() {#setsupplychainid}

Barcode C の最大値は 99、Barcode L の最大値は 999999 です。

### setVersionID() {#setversionid}

現在 "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use)
