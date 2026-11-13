---
title: "QualitySettings"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings는 인식 품질 및 속도를 수동으로 구성할 수 있게 합니다.<br/>            내장된 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxQuality를 사용하여 QualitySettings를 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있습니다.<br/>            QualitySettings의 기본값은 NormalQuality입니다.

QualitySettings 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| high_performance | HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드를 잘 인식합니다. |
| normal_quality | NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다. |
| high_quality | HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다. 심하게 손상된 바코드도 감지할 수 있습니다. |
| max_quality | MaxQuality 인식 품질 프리셋. 이 프리셋은 모든 가능한 바코드, 심지어 잘못된 바코드까지 인식하도록 개발되었습니다. |
| x_dimension | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드. |
| minimal_x_dimension | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀)입니다. |
| barcode_quality | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요해 인식 속도가 느려집니다. |
| deconvolution | Deconvolution(이미지 복원) 모드는 이미지 손상 수준을 정의합니다. 원래 Deconvolution은 카메라로 이미지를 얻는 과정에서 흐림과 같은 자연 함수에 의해 손상된(컨볼루션된) 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, <br/>            가장 잘 알려진 함수인 샤프 또는 수학적 형태학과 같은 함수를 확인해야 합니다. |
| inverse_image | 색상이 반전된(휘도) 이미지에서 바코드 추가 인식을 활성화하거나 비활성화하는 모드. |
| complex_background | 컬러 이미지에서 컬러 바코드 추가 인식을 활성화하거나 비활성화하는 모드. |
| allow_incorrect_barcodes | 엔진이 체크섬이나 값이 잘못된 바코드를 인식하도록 허용합니다. 이 모드는 텍스트가 잘못된 손상된 바코드를 인식하는 데 사용할 수 있습니다. |

### 또 보기

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

