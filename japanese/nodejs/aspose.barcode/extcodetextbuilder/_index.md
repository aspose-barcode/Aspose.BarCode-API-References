---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "拡張コードテキストモードの自動コードテキスト生成のためのヘルパークラス"
type: docs
weight: 400
url: /ja/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

拡張コードテキストモードの自動コードテキスト生成のためのヘルパークラス

```js
new ExtCodetextBuilder()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Extended Channel Identifier を使用してコードテキストを追加します |
| [addPlainCodetext(codetext)](#addplaincodetext) | 拡張コードテキスト項目にプレーンコードテキストを追加します |
| [clear()](#clear) | 拡張コードテキスト項目をクリアします |
| [getExtendedCodetext()](#getextendedcodetext) | 生成項目リストから拡張コードテキストを生成します |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Extended Channel Identifier を使用してコードテキストを追加します

| パラメータ | 説明 |
| --- | --- |
| ECIEncoding | 拡張チャネル識別子 |
| codetext | Unicode のコードテキストを Extended Channel Identifier を使用した拡張コードテキスト項目として追加します |

### addPlainCodetext(codetext) {#addplaincodetext}

拡張コードテキスト項目にプレーンコードテキストを追加します

| パラメータ | 説明 |
| --- | --- |
| codetext | 拡張コードテキスト項目として追加する Unicode のコードテキスト |

### clear() {#clear}

拡張コードテキスト項目をクリアします

### getExtendedCodetext() {#getextendedcodetext}

生成項目リストから拡張コードテキストを生成します

**Returns:** Return string of extended codetext
