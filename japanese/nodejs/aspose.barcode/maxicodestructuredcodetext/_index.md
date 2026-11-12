---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "モード 2、3 用の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードする基底クラスです。"
type: docs
weight: 700
url: /ja/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

モード 2、3 用の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードする基底クラスです。

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals(obj)](#equals) | このインスタンスが指定された値と等しいかどうかを示す値を返します。 |
| [getConstructedCodetext()](#getconstructedcodetext) | codetext を構築します |
| [getCountryCode()](#getcountrycode) | 3 桁の国コードを識別します。 |
| [getHashCode()](#gethashcode) | このインスタンスのハッシュコードを返します。 |
| [getPostalCode()](#getpostalcode) | 郵便番号を識別します。モード 2 では 9 桁、モード 3 では 6 文字の英数字である必要があります。 |
| [getSecondMessage()](#getsecondmessage) | バーコードの第2メッセージを識別します。 |
| [getServiceCategory()](#getservicecategory) | 3 桁のサービスカテゴリを識別します。 |
| [initFromString(constructedCodetext)](#initfromstring) | 構築された codetext からインスタンスを初期化します。 |
| [setCountryCode()](#setcountrycode) | 3 桁の国コードを識別します。 |
| [setPostalCode()](#setpostalcode) | 郵便番号を識別します。モード 2 では 9 桁、モード 3 では 6 文字の英数字である必要があります。 |
| [setSecondMessage()](#setsecondmessage) | バーコードの第2メッセージを識別します。 |
| [setServiceCategory()](#setservicecategory) | 3 桁のサービスカテゴリを識別します。 |

### equals(obj) {#equals}

このインスタンスが指定された値と等しいかどうかを示す値を返します。

| パラメータ | 説明 |
| --- | --- |
| obj | このインスタンスと比較する値 |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

codetext を構築します

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

3 桁の国コードを識別します。

### getHashCode() {#gethashcode}

このインスタンスのハッシュコードを返します。

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

郵便番号を識別します。モード 2 では 9 桁、モード 3 では 6 文字の英数字である必要があります。

### getSecondMessage() {#getsecondmessage}

バーコードの第2メッセージを識別します。

### getServiceCategory() {#getservicecategory}

3 桁のサービスカテゴリを識別します。

### initFromString(constructedCodetext) {#initfromstring}

構築された codetext からインスタンスを初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |

### setCountryCode() {#setcountrycode}

3 桁の国コードを識別します。

### setPostalCode() {#setpostalcode}

郵便番号を識別します。モード 2 では 9 桁、モード 3 では 6 文字の英数字である必要があります。

### setSecondMessage() {#setsecondmessage}

バーコードの第2メッセージを識別します。

### setServiceCategory() {#setservicecategory}

3 桁のサービスカテゴリを識別します。
