---
title: "클래스 BarCodeGeneratorControl"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl 클래스. BarCode Windows 컨트롤을 툴박스 패널로 이동하고 Aspose.BarCode.dll을 추가하면 BarcodeGeneratorControl이 나타납니다. 그냥 끌어다 Windows 폼에 놓으세요. see  see"
type: docs
weight: 1800
url: /ko/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows 컨트롤, 툴박스 패널로 이동하여 Aspose.BarCode.dll을 추가하면 BarcodeGeneratorControl이 나타납니다. 그냥 끌어서 Windows 폼에 놓으세요. see  see

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | 바코드가 자동으로 크기 조정되는 모드를 가져오거나 설정합니다. 기본값은 AutoSizeMode.None입니다. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | 바코드 이미지의 배경 색상. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | `[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/)` 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 BarCode 이미지 높이. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Barcode 패딩 매개변수 [`Padding`](../../aspose.barcode.generation/padding/)를 가져오거나 설정합니다. |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | BarCode의 인코드 유형(심볼로지). 현재 심볼로지를 가져오려면 [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/)를 사용하세요. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | `[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/)` 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 BarCode 이미지 너비. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | 바 색상. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | 1D 바코드 막대의 높이. [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | 테두리 매개변수 [`BorderParameters`](../../aspose.barcode.generation/borderparameters/)를 가져오거나 설정합니다. |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | BarCode 이미지 위의 캡션. [`CaptionUI`](../captionui/)를 참조하세요. |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | BarCode 이미지 아래의 캡션. [`CaptionUI`](../captionui/)를 참조하세요. |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Code128 및 GS1Code128 바코드의 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | 인코드될 데이터, 바코드 종류에 따라 서로 다른 CodeText 길이 제한이 있을 수 있습니다. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | CodeText 매개변수 [`CodetextParametersUI`](../codetextparametersui/)를 가져오거나 설정합니다. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | BarCode의 인코드 유형(심볼로지). 현재 심볼로지를 가져오려면 [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/)를 사용하세요. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | 막대가 채워졌는지 여부를 나타내는 값을 가져오거나 설정합니다. 1D 바코드에만 적용됩니다. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | 1D 바코드 생성 시 체크섬을 활성화합니다. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | BarCode 이미지의 해상도를 가져오거나 설정합니다. 두 차원 모두에 하나의 값이 사용됩니다. 기본값: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | BarCode 이미지 회전 각도, 단위는 도이며, 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아니면 스캐너가 이미지를 읽는 데 어려움이 증가할 수 있습니다. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | 특정 매개변수 |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | 1D 바코드에만 적용됩니다. codetext가 올바르지 않고 값이 true로 설정된 경우 예외가 발생합니다. 그렇지 않으면 codetext가 바코드 사양에 맞게 수정됩니다. 예외는 항상 발생합니다: Databar 심볼로지에서 codetext가 올바르지 않은 경우. 예외는 발생하지 않습니다: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 심볼로지에서 codetext가 올바르지 않은 경우. |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | 이미지를 렌더링할 때 안티앨리어싱 모드를 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | 와이드 바와 나로드 바의 비율. 기본값: 3, 즉 와이드 바는 나로드 바보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII에 사용됩니다. |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-차원은 BarCode 바 또는 공백 단위의 최소 너비입니다. 이를 증가시키면 전체 바코드 이미지 너비가 증가합니다. [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다. |

### 또 보기

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


