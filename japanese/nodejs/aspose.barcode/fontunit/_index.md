---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "テキストの特定のフォーマットを定義し、フォントファミリー、サイズ、スタイル属性を含み、サイズは Unit 値プロパティで指定します。"
type: docs
weight: 410
url: /ja/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

テキストの特定のフォーマットを定義し、フォントファミリー、サイズ、スタイル属性を含み、サイズは Unit 値プロパティで指定します。

```js
new FontUnit()
```

**Example:**

```js
This sample shows how to create and save a BarCode image.

  let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
  generator.getParameters().getCaptionAbove().setText("CAPTION ABOOVE");
  generator.getParameters().getCaptionAbove().setVisible(true);
  generator.getParameters().getCaptionAbove().getFont().setStyle(FontStyle.ITALIC);
  generator.getParameters().getCaptionAbove().getFont().getSize().setPoint(25);
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getFamilyName()](#getfamilyname) | この Font のフォント名を取得します。 |
| [getSize()](#getsize) | この FontUnit のサイズを Unit 値で取得します。 |
| [getStyle()](#getstyle) | この FontUnit のスタイル情報を取得します。 |
| [setFamilyName()](#setfamilyname) | この Font のフォント名を設定します。 |
| [setStyle()](#setstyle) | この FontUnit のスタイル情報を設定します。 |

### getFamilyName() {#getfamilyname}

この Font のフォント名を取得します。

### getSize() {#getsize}

この FontUnit のサイズを Unit 値で取得します。

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

この FontUnit のスタイル情報を取得します。

### setFamilyName() {#setfamilyname}

この Font のフォント名を設定します。

### setStyle() {#setstyle}

この FontUnit のスタイル情報を設定します。
