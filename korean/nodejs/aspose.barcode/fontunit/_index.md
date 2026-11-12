---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴, 크기 및 스타일 속성이 포함되고 크기는 Unit 값 속성에 있습니다."
type: docs
weight: 410
url: /ko/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴, 크기 및 스타일 속성이 포함되고 크기는 Unit 값 속성에 있습니다.

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

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getFamilyName()](#getfamilyname) | 이 Font의 글꼴 이름을 가져옵니다. |
| [getSize()](#getsize) | 이 FontUnit의 크기를 Unit 값으로 가져옵니다. |
| [getStyle()](#getstyle) | 이 FontUnit에 대한 스타일 정보를 가져옵니다. |
| [setFamilyName()](#setfamilyname) | 이 Font의 글꼴 이름을 설정합니다. |
| [setStyle()](#setstyle) | 이 FontUnit에 대한 스타일 정보를 설정합니다. |

### getFamilyName() {#getfamilyname}

이 Font의 글꼴 이름을 가져옵니다.

### getSize() {#getsize}

이 FontUnit의 크기를 Unit 값으로 가져옵니다.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

이 FontUnit에 대한 스타일 정보를 가져옵니다.

### setFamilyName() {#setfamilyname}

이 Font의 글꼴 이름을 설정합니다.

### setStyle() {#setstyle}

이 FontUnit에 대한 스타일 정보를 설정합니다.
