---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

USA 운전 면허 PDF417 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.

USADriveIdCodetext 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| USADriveIdCodetext() | USADriveIdCodetext 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| issuer_identification_number | 이 번호는 <br/>            발행 관할 구역을 고유하게 식별하며 ISO<br/>            발행 기관(AAMVA)에 연락하여 얻을 수 있습니다. 전체 6자리 IIN을 인코딩해야 합니다. |
| aamva_version_number | AAMVA 버전 번호 00-99 |
| jurisdiction_version_number | 관할 구역 버전 번호 00-99 |
| number_of_entries | 하위 파일 수 00-99 |
| subfile_designator | 다음 하위 파일, 유형, 오프셋 및 길이에 대한 정보를 포함합니다. <br/>            중요: 유형만 설정하면 오프셋과 길이는 자동으로 설정됩니다. |
| mandatory_elements | 카드의 필수 요소(필드) |
| optional_elements | 카드의 선택적 요소(필드) |
| jurisdiction_specific_subfile | 관할 구역별 필드 |
## 메서드
| 이름 | 설명 |
| :- | :- |
| get_constructed_codetext() | USA DL 데이터에서 코드텍스트를 구성합니다 |
| init_from_string(constructed_codetext) | 코드텍스트에서 USA DL 객체를 초기화합니다 |
| get_barcode_type() | USA DL의 바코드 유형(Pdf417)을 반환합니다 |
| save_to_xml(stream) | XML로 저장합니다 |

### 또 보기

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

