---
title: "열거형 TwoDComponentType"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.TwoDComponentType 열거형. 2D 구성 요소 유형"
type: docs
weight: 1730
url: /ko/net/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enumeration

2D 구성 요소 유형

```csharp
public enum TwoDComponentType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | 2D 구성 요소 유형을 자동으로 선택 |
| CC_A | `1` | CC-A 유형의 2D 구성 요소. MicroPDF417의 구조적 변형입니다. |
| CC_B | `2` | CC-B 유형의 2D 구성 요소. MicroPDF417 심볼입니다. |
| CC_C | `3` | CC-C 유형의 2D 구성 요소. PDF417 심볼입니다. |

## 예제

이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드 텍스트와 2D 코드 텍스트는 '/' 기호로 구분된다는 점에 유의하십시오.

```csharp
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

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


