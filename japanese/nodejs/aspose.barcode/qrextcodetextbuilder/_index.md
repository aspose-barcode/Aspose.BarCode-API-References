---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "ExtendedCodetext モードの QREncodeMode 用 2D QR バーコードの拡張コードテキストジェネレータです。BarCodeBuilder の Display2DText プロパティを使用して、表示テキストを rem に設定します"
type: docs
weight: 820
url: /ja/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

ExtendedCodetext モードの QREncodeMode 用 2D QR バーコードの拡張コードテキストジェネレータです。BarCodeBuilder の Display2DText プロパティを使用して、表示テキストを管理文字を削除するように設定します。

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | 指定された QR コンパクションモードを使用してコードテキストを拡張コードテキスト項目に追加します。 |
| [addFNC1FirstPosition()](#addfnc1firstposition) | 拡張コードテキスト項目の先頭位置に FNC1 を追加します |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | 拡張コードテキスト項目にグループ区切り文字 (GS - '\\u001D') を追加します |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | 拡張コードテキスト項目の第2位置に FNC1 を追加します |
| [clear()](#clear) | 拡張コードテキスト項目をクリアします |
| [getExtendedCodetext()](#getextendedcodetext) | 拡張コードテキストリストから拡張コードテキストを生成します。 |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

指定された QR コンパクションモードを使用してコードテキストを拡張コードテキスト項目に追加します。

| パラメータ | 説明 |
| --- | --- |
| モード | コードテキストの QR コンパクションモードです。 |
| codetext | 拡張コードテキスト項目として追加する Unicode のコードテキストです。 |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

拡張コードテキスト項目の先頭位置に FNC1 を追加します

### addFNC1GroupSeparator() {#addfnc1groupseparator}

拡張コードテキスト項目にグループ区切り文字 (GS - '\\u001D') を追加します

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

拡張コードテキスト項目の第2位置に FNC1 を追加します

| パラメータ | 説明 |
| --- | --- |
| codetext | 第2位置の FNC1 の値 |

### clear() {#clear}

拡張コードテキスト項目をクリアします

### getExtendedCodetext() {#getextendedcodetext}

拡張コードテキストリストから拡張コードテキストを生成します。

**Returns:** Extended codetext as string
