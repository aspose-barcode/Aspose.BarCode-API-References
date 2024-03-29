---
title: AztecSymbolMode
second_title: .NET API 참조용 Aspose.BarCode
description: 아즈텍 기호 모드를 지정합니다.
type: docs
weight: 670
url: /ko/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

아즈텍 기호 모드를 지정합니다.

```csharp
public enum AztecSymbolMode
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | Aztec에 가장 적합한 기호(컴팩트 또는 전체 범위)를 자동으로 선택하도록 지정합니다. 기본값입니다. |
| Compact | `1` | Aztec에 대한 압축 기호를 지정합니다. Aztec 압축 기호는 1, 2, 3 또는 4개의 레이어만 허용합니다. |
| FullRange | `2` | Aztec에 대한 전체 범위 기호를 지정합니다. Aztec 전체 범위 기호는 1~32개의 레이어를 허용합니다. |
| Rune | `3` | Aztec의 룬 기호를 지정합니다. Aztec 룬은 일련의 작지만 뚜렷한 기계 판독 가능 표시입니다. 0에서 255까지의 숫자 값만 허용합니다. |

### 예

이 샘플은 Aztec 기호 모드를 변경하고 바코드 이미지를 저장하는 방법을 보여줍니다.

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

### 또한보십시오

* 네임스페이스 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
