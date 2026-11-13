---
title: "QrParameters"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

QR 매개변수.

QrParameters 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| eci_encoding | 확장 채널 해석 식별자. 바코드 리더에게 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다.<br/>            현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다.<br/>            MicroQR에서는 지원되지 않습니다. |
| encode_mode | BarCode의 인코딩 모드에 대한 QR 심볼 유형.<br/>            기본값: QREncodeMode.Auto. |
| error_level | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준.<br/>             낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel을 참조하십시오. |
| version | QR 코드 버전. Version1부터 Version40까지.<br/>            기본값은 QRVersion.Auto입니다. |
| micro_qr_version | MicroQR 코드 버전. M1 버전부터 M4 버전까지.<br/>            기본값은 MicroQRVersion.Auto입니다. |
| rect_micro_qr_version | RectMicroQR 코드 버전. R7x59 버전부터 R17x139 버전까지.<br/>            기본값은 RectMicroQRVersion.Auto입니다. |
| aspect_ratio | 2D 바코드 모듈의 높이/너비 비율. |
| structured_append | QR 구조화된 추가 매개변수.<br/>            구조화된 추가 모드는 MicroQR 및 RectMicroQR 바코드에서 지원되지 않습니다. |
| encode_gs1_separator_in_byte_mode |  |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

