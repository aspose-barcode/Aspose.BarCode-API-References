---
title: "Aspose::BarCode::Generation::FontUnit class"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::FontUnit class. C++에서 Unit 값 속성의 크기를 포함한 글꼴, 크기 및 스타일 속성을 포함하는 텍스트의 특정 형식을 정의합니다."
type: docs
weight: 2500
url: /ko/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


글꼴, 크기 및 스타일 속성을 포함한 텍스트의 특정 형식을 정의합니다. 여기서 크기는 [Unit](../unit/) 값 속성에 있습니다.

```cpp
class FontUnit : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | 이 Font의 글꼴 이름을 가져옵니다. |
| [get_Size](./get_size/)() const | 이 [FontUnit](./)의 크기를 [Unit](../unit/) 값으로 가져옵니다. |
| [get_Style](./get_style/)() const | 이 [FontUnit](./)에 대한 스타일 정보를 가져옵니다. |
| [set_FamilyName](./set_familyname/)(System::String) | 이 Font의 글꼴 이름을 설정합니다. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | 이 [FontUnit](./)에 대한 스타일 정보를 설정합니다. |
## 비고


이 샘플은 [BarCode](../../aspose.barcode/) 이미지를 생성하고 저장하는 방법을 보여줍니다.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
