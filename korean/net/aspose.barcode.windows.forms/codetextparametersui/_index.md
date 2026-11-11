---
title: "클래스 CodetextParametersUI"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Windows.Forms.CodetextParametersUI 클래스. Codetext 매개변수"
type: docs
weight: 1820
url: /ko/net/aspose.barcode.windows.forms/codetextparametersui/
---
## CodetextParametersUI class

코드텍스트 매개변수.

```csharp
public class CodetextParametersUI
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Alignment](../../aspose.barcode.windows.forms/codetextparametersui/alignment/) { get; set; } | 코드 텍스트의 정렬을 가져오거나 설정합니다. 기본값: StringAlignment.Center. |
| [Color](../../aspose.barcode.windows.forms/codetextparametersui/color/) { get; set; } | 표시되는 CodeText의 색상을 지정합니다. 기본값: Color.Black. |
| [Font](../../aspose.barcode.windows.forms/codetextparametersui/font/) { get; set; } | 표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 FontMode.Auto로 설정된 경우 무시됩니다. |
| [FontMode](../../aspose.barcode.windows.forms/codetextparametersui/fontmode/) { get; set; } | FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다. AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation에서 특히 FontMode.Auto를 사용하는 것이 권장됩니다. 기본값: FontMode.Auto. |
| [Location](../../aspose.barcode.windows.forms/codetextparametersui/location/) { get; set; } | CodeText 표시 위치를 지정합니다. CodeText를 숨기려면 CodeLocation.None으로 설정하십시오. 기본값: 1D 바코드의 경우 CodeLocation.Below, 2D 바코드의 경우 CodeLocation.None. |
| [Space](../../aspose.barcode.windows.forms/codetextparametersui/space/) { get; } | `[`Unit`](../../aspose.barcode.generation/unit/)` 값으로 CodeText와 BarCode 사이의 간격. 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에 대해서는 무시됩니다. |
| [TwoDDisplayText](../../aspose.barcode.windows.forms/codetextparametersui/twoddisplaytext/) { get; set; } | 2D 바코드에서 codetext 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/codetextparametersui/tostring/)() | 이 [`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### 또 보기

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


