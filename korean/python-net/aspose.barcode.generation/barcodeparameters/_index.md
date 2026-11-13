---
title: "BarcodeParameters"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

바코드 생성 매개변수.

BarcodeParameters 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| x_dimension | x-dimension은 바코드 바 또는 공백 단위의 최소 너비입니다.<br/>            이를 증가시키면 전체 바코드 이미지 너비가 증가합니다.<br/>            [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다. |
| bar_height | 1D 바코드 바의 높이를 [Unit](/barcode/python-net/aspose.barcode.generation/unit/) 값으로 지정합니다.<br/>            [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우 무시됩니다. |
| bar_color | 바 색상.<br/>            기본값: Color.Black. |
| padding | 바코드 패딩.<br/>            기본값: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Code128 및 GS1Code128 바코드의 인간이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | 1D 바코드에만 적용됩니다.<br/>            codetext가 올바르지 않고 값이 true로 설정된 경우 예외가 발생합니다. 그렇지 않으면 codetext가 바코드 사양에 맞게 수정됩니다.<br/>            다음 경우에는 codetext가 올바르지 않으면 항상 예외가 발생합니다: Databar 심볼로지.<br/>            다음 경우에는 codetext가 올바르지 않더라도 예외가 발생하지 않습니다: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 심볼로지. |
| wide_narrow_ratio | 넓은 바와 좁은 바의 비율.<br/>            기본값: 3, 즉 넓은 바는 좁은 바보다 3배 넓습니다.<br/>            ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII에 사용됩니다. |
| code_text_parameters | Codetext 매개변수. |
| filled_bars | 바가 채워졌는지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            1D 바코드에만 적용됩니다.<br/>            기본값: true. |
| bar_width_reduction | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 가져오거나 설정합니다.<br/>            기본값: 0 |
| postal | 우편 매개변수. Postnet 및 Planet에 사용됩니다. |
| patch_code | PatchCode 매개변수. |
| australian_post | AustralianPost 바코드 매개변수. |
| data_bar | Databar 매개변수. |
| gs1_composite_bar | GS1 Composite Bar 매개변수. |
| codablock | Codablock 매개변수. |
| data_matrix | DataMatrix 매개변수. |
| code_16k | Code16K 매개변수. |
| dot_code | DotCode 매개변수. |
| itf | ITF 매개변수. |
| pdf417 | PDF417 매개변수. |
| qr | QR, MicroQR 및 RectMicroQR 매개변수. |
| supplement | 보조 매개변수. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN에 사용됩니다. |
| maxi_code | MaxiCode 매개변수. |
| aztec | Aztec 매개변수. |
| code128 | Code128 매개변수. |
| codabar | Codabar 매개변수. |
| coupon | 쿠폰 매개변수. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon에 사용됩니다. |
| han_xin | HanXin 매개변수. |
| gs1 | GS1 매개변수. |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

