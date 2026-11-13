---
title: "CodetextParameters"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Codetext 매개변수.

CodetextParameters 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| two_d_display_text | 2D 바코드에서 코드텍스트 대신 표시될 텍스트입니다.<br/>            사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | FontMode를 지정합니다. FontMode가 Auto로 설정된 경우, 글꼴 크기는 xDimension 값에 따라 자동으로 계산됩니다.<br/>            특히 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation에서 FontMode.Auto를 사용하는 것이 권장됩니다.<br/>            기본값: FontMode.Auto. |
| font | 표시되는 CodeText의 글꼴을 지정합니다.<br/>            기본값: Arial 5pt regular.<br/>            FontMode가 FontMode.Auto로 설정된 경우 무시됩니다. |
| space | [Unit](/barcode/python-net/aspose.barcode.generation/unit/) 값에서 CodeText와 BarCode 사이의 간격입니다.<br/>            기본값: 2pt.<br/>            EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에 대해서는 무시됩니다. |
| 정렬 | 코드 텍스트의 정렬을 가져오거나 설정합니다.<br/>            기본값: StringAlignment.Center. |
| 색상 | 표시되는 CodeText의 색상을 지정합니다.<br/>            기본값: Color.Black. |
| 위치 | 표시되는 CodeText 위치를 지정하고, CodeText를 숨기려면 CodeLocation.None으로 설정합니다.<br/>            기본값: 1D 바코드의 경우 CodeLocation.Below, 2D 바코드의 경우 CodeLocation.None. |
| no_wrap | 텍스트 내에서 단어 줄바꿈(줄 바꿈)을 지정합니다.<br/>            기본값: false. |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

