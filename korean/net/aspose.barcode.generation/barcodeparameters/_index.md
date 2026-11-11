---
title: "클래스 BarcodeParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.BarcodeParameters 클래스. 바코드 생성 매개변수"
type: docs
weight: 1010
url: /ko/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

바코드 생성 매개변수.

```csharp
public class BarcodeParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | AustralianPost 바코드 매개변수. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Aztec 매개변수. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | 바 색상. 기본값: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | 1D 바코드 바의 높이를 [`Unit`](../unit/) 값으로 지정합니다. [`AutoSizeMode`](../basegenerationparameters/autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 가져오거나 설정합니다. 기본값: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Code128 및 GS1Code128 바코드의 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Codabar 매개변수. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Codablock 매개변수. |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Code128 매개변수. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Code16K 매개변수. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | 코드텍스트 매개변수. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | 쿠폰 매개변수. UpcaGs1DatabarCoupon 및 UpcaGs1Code128Coupon에 사용됩니다. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Databar 매개변수. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | DataMatrix 매개변수. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | DotCode 매개변수. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | 바가 채워졌는지 여부를 나타내는 값을 가져오거나 설정합니다. 1D 바코드에만 적용됩니다. 기본값: true. |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | GS1 매개변수. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | GS1 복합 바 매개변수. |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | HanXin 매개변수. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | 1D 바코드 생성 시 체크섬을 활성화합니다. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | ITF 매개변수. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | MaxiCode 매개변수. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | 바코드 패딩. 기본값: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | PatchCode 매개변수. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417 매개변수. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | 우편 매개변수. Postnet 및 Planet에 사용됩니다. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR, MicroQR 및 RectMicroQR 매개변수. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | 보충 매개변수. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN에 사용됩니다. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | 1D 바코드에만 적용됩니다. 코드 텍스트가 올바르지 않고 값이 true로 설정된 경우 예외가 발생합니다. 그렇지 않으면 코드 텍스트가 바코드 사양에 맞게 자동으로 수정됩니다. 다음 경우에는 항상 예외가 발생합니다: Databar 심볼이 코드가 올바르지 않은 경우. 다음 경우에는 예외가 발생하지 않습니다: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 심볼이 코드가 올바르지 않은 경우. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | 와이드 바와 나로드 바의 비율. 기본값: 3, 즉 와이드 바는 나로드 바보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII에 사용됩니다. |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-차원은 BarCode 바 또는 공백 단위의 최소 너비입니다. 이를 증가시키면 전체 바코드 이미지 너비가 증가합니다. [`AutoSizeMode`](../basegenerationparameters/autosizemode/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다. |

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


