---
title: "열거형 AztecSymbolMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.AztecSymbolMode 열거형. Aztec 심볼 모드를 지정합니다."
type: docs
weight: 970
url: /ko/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Aztec 심볼 모드를 지정합니다.

```csharp
public enum AztecSymbolMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | Aztec에 대해 최적의 심볼(Compact 또는 Full-range)을 자동으로 선택하도록 지정합니다. 이는 기본값입니다. |
| Compact | `1` | Aztec용 Compact 심볼을 지정합니다. Aztec Compact 심볼은 1, 2, 3 또는 4 레이어만 허용합니다. |
| FullRange | `2` | Aztec용 Full-range 심볼을 지정합니다. Aztec Full-range 심볼은 1에서 32 레이어까지 허용합니다. |
| Rune | `3` | Aztec용 Rune 심볼을 지정합니다. Aztec Rune은 작지만 구별되는 기계 판독 마크의 시리즈입니다. 0에서 255까지의 숫자 값만 허용합니다. |

## 예제

이 샘플은 Aztec Symbol 모드를 변경하고 BarCode 이미지를 저장하는 방법을 보여줍니다.

```csharp
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

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


