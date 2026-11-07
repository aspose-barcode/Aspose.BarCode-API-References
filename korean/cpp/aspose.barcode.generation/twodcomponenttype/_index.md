---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " enum. C++에서 2D 구성 요소의 유형."
type: docs
weight: 8700
url: /ko/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


2D 구성 요소 유형

```cpp
enum class TwoDComponentType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 자동 | 0 | 2D 구성 요소 유형을 자동 선택 |
| CC_A | 1 | CC-A 유형의 2D 구성 요소입니다. MicroPDF417의 구조적 변형입니다. |
| CC_B | 2 | CC-B 유형의 2D 구성 요소입니다. MicroPDF417 심볼입니다. |
| CC_C | 3 | CC-C 유형의 2D 구성 요소입니다. PDF417 심볼입니다. |

## 비고


이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드텍스트와 2D 코드텍스트는 '/' 기호로 구분됩니다.
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // 2D 구성 요소의 종횡비
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // 1D 및 2D 구성 요소의 X-차원
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // 1D 구성 요소의 높이
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
