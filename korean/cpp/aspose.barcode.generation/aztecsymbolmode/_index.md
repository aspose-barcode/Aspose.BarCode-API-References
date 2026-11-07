---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " enum. C++에서 Aztec 기호 모드를 지정합니다."
type: docs
weight: 5400
url: /ko/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Aztec 심볼 모드를 지정합니다.

```cpp
enum class AztecSymbolMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 자동 | 0 | Aztec에 대해 최적의 기호(Compact 또는 Full-range)를 자동으로 선택하도록 지정합니다. 기본값입니다. |
| Compact | 1 | Aztec용 Compact 기호를 지정합니다. Aztec Compact 기호는 1, 2, 3 또는 4 레이어만 허용합니다. |
| FullRange | 2 | Aztec용 Full-range 기호를 지정합니다. Aztec Full-range 기호는 1에서 32 레이어까지 허용합니다. |
| Rune | 3 | Aztec용 Rune 기호를 지정합니다. Aztec Rune은 작지만 구별되는 기계 판독 마크의 시리즈입니다. 0에서 255까지의 숫자 값만 허용합니다. |

## 비고


이 샘플은 Aztec Symbol 모드를 변경하고 [BarCode](../../aspose.barcode/) 이미지를 저장하는 방법을 보여줍니다.
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
