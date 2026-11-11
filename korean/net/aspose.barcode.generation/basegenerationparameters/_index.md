---
title: "클래스 BaseGenerationParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.BaseGenerationParameters 클래스. 바코드 이미지 생성 매개변수"
type: docs
weight: 1030
url: /ko/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

바코드 이미지 생성 매개변수.

```csharp
public class BaseGenerationParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | 자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | 바코드 이미지의 배경 색상. 기본값: Color.White. Color를 참조하십시오. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | 모든 바코드 속성을 포함하는 [`BarcodeParameters`](../barcodeparameters/)를 가져옵니다. |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | 바코드 테두리의 모든 구성 속성을 포함하는 [`BorderParameters`](../borderparameters/)를 가져옵니다. |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | 바코드 이미지 위의 캡션. [`CaptionParameters`](../captionparameters/)를 참조하십시오. |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | 바코드 이미지 아래의 캡션. [`CaptionParameters`](../captionparameters/)를 참조하십시오. |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | 이미지 매개변수. [`ImageParameters`](../imageparameters/)를 참조하십시오. |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | [`AutoSizeMode`](./autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 BarCode 이미지 높이. |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | [`AutoSizeMode`](./autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 BarCode 이미지 너비. |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | BarCode 이미지의 해상도를 가져오거나 설정합니다. 두 차원 모두에 하나의 값이 사용됩니다. 기본값: 96 dpi. |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | BarCode 이미지 회전 각도(도 단위), 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아니면 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: 0. |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | 이미지를 렌더링할 때 안티앨리어싱 모드를 사용할지 여부를 나타내는 값을 가져오거나 설정합니다. |

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


