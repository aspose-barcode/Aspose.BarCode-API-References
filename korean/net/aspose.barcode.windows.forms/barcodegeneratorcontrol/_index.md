---
title: BarCodeGeneratorControl
second_title: .NET API 참조용 Aspose.BarCode
description: BarCode Windows Control 도구 상자 패널로 이동하여 Aspose.BarCode.dll 를 추가하면 BarcodeGeneratorControl이 나타나는 것을 볼 수 있습니다. 참조
type: docs
weight: 1320
url: /ko/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, 도구 상자 패널로 이동하여 Aspose.BarCode.dll, 를 추가하면 BarcodeGeneratorControl이 나타나는 것을 볼 수 있습니다. 참조

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | 바코드가 자동으로 크기를 조정하는 모드를 가져오거나 설정합니다. 기본값은 AutoSizeMode.None입니다. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | 바코드 이미지의 배경색. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | 바코드 이미지 높이[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation. 로 설정됨 |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | 바코드 패딩 매개변수를 가져오거나 설정합니다.[`Padding`](../../aspose.barcode.generation/padding/) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | 바코드의 인코딩 유형(기호). 사용[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) 현재 기호를 얻으려면. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | 바코드 이미지 너비[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation. 로 설정됨 |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | 막대 색상. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | 1D 바코드 바의 높이. 다음의 경우 무시됨[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation. 로 설정됨 |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | 테두리 매개변수를 가져오거나 설정합니다.[`BorderParameters`](../../aspose.barcode.generation/borderparameters/) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | 캡션 바코드 이미지 위. 보다[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | 캡션 바코드 이미지 아래. 보다[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | 인코딩할 데이터, 바코드 유형에 따라 CodeText 길이 제한이 다를 수 있습니다. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | CodeText 매개변수를 가져오거나 설정합니다.[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape/) { get; set; } | CodeText 속성에서 문자 "\"를 이스케이프 문자로 설명하는지 여부를 나타냅니다. Pdf417, DataMatrix, Code128에만 사용됨 EnableEscape가 true인 경우 "\"는 특수 이스케이프 문자로 설명됩니다. 그렇지 않으면 "\"는 일반 문자로 작동합니다. Aspose.BarCode는 ASCII 제어 코드 문자에 대한 10진수 ASCII 코드 및 니모닉 입력을 지원합니다. 예를 들어 \013 및 \\CR은 CR을 나타냅니다. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | 바코드의 인코딩 유형(기호). 사용[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) 현재 기호를 얻으려면. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | 막대가 채워졌는지 여부를 나타내는 값을 가져오거나 설정합니다. 1D 바코드에만 해당합니다. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | 1D 바코드 생성 중 체크섬을 활성화합니다. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | 바코드 이미지의 해상도를 가져오거나 설정합니다. 두 치수에 대해 하나의 값. 기본값: 96dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | 바코드 이미지 회전 각도, 도 단위로 측정(예: RotationAngle = 0 또는 RotationAngle = 360은 회전 없음을 의미) |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | 특정 매개변수 |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | 1D 바코드에만 해당. 코드 텍스트가 올바르지 않고 값이 true로 설정된 경우 예외가 발생합니다. 그렇지 않으면 코드 텍스트가 바코드 사양과 일치하도록 수정됩니다. 코드 텍스트가 잘못된 경우 데이터바 기호에 대해 항상 예외가 발생합니다. 코드 텍스트가 잘못된 경우 AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 기호에 대해 예외가 항상 발생하지 않습니다. . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | 넓은 막대 대 좁은 막대 비율. 기본값: 3, 즉 넓은 막대는 좁은 막대보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost에 사용 , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-dimension은 바코드 막대 또는 공백 단위의 가장 작은 너비입니다. 이 값을 높이면 전체 바코드 이미지 너비가 늘어납니다. 다음 경우에는 무시됩니다.[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation. 로 설정됨 |

### 또한보십시오

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* 네임스페이스 [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
