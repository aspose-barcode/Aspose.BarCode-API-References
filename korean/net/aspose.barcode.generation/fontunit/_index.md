---
title: "FontUnit 클래스"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.FontUnit 클래스. 텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴 크기와 스타일 속성이 포함되고 크기는 Unit 값 속성에 있습니다."
type: docs
weight: 1320
url: /ko/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

텍스트에 대한 특정 형식을 정의하며, 여기에는 글꼴, 크기 및 스타일 속성이 포함되고 크기는 Unit 값 속성에 있습니다.

```csharp
public sealed class FontUnit
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | 이 Font의 글꼴 이름을 가져오거나 설정합니다. |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | 이 FontUnit의 크기를 Unit 값으로 가져오거나 설정합니다. |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | 이 FontUnit의 스타일 정보를 가져오거나 설정합니다. |

## 예제

이 샘플은 BarCode 이미지를 생성하고 저장하는 방법을 보여줍니다.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


