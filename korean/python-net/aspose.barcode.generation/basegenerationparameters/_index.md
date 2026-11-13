---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

바코드 이미지 생성 매개변수.

BaseGenerationParameters 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| use_anti_alias | 이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 가져오거나 설정합니다 |
| back_color | 바코드 이미지의 배경 색상.<br/>            기본값: Color.White.<br/>            자세한 내용은 [Color](/barcode/python-net/aspose.drawing/color/)을(를) 참조하십시오. |
| 해상도 | BarCode 이미지의 해상도를 가져오거나 설정합니다.<br/>            두 차원에 대해 동일한 값을 사용합니다.<br/>            기본값: 96 dpi. |
| rotation_angle | BarCode 이미지 회전 각도(단위:도). 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다.<br/>            RotationAngle가 90, 180, 270 또는 0이 아닌 경우 스캐너가 이미지를 읽기 어려워질 수 있습니다.<br/>            기본값: 0. |
| caption_above | BarCode 이미지 위의 캡션. 자세한 내용은 [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/)을(를) 참조하십시오. |
| caption_below | BarCode 이미지 아래의 캡션. 자세한 내용은 [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/)을(를) 참조하십시오. |
| image | 이미지 매개변수. 자세한 내용은 [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/)을(를) 참조하십시오. |
| auto_size_mode | 자동 크기 조정 모드의 다양한 유형을 지정합니다.<br/>            기본값: AutoSizeMode.None. |
| image_height | BarCode 이미지 높이는 [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우. |
| image_width | BarCode 이미지 너비는 [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) 속성이 AutoSizeMode.Nearest 또는 AutoSizeMode.Interpolation으로 설정된 경우. |
| barcode | [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/)을 가져와 모든 바코드 속성을 포함합니다. |
| border | [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/)을 가져와 바코드 테두리의 모든 구성 속성을 포함합니다. |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

