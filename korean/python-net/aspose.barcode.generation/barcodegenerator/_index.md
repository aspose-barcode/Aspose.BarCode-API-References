---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

백엔드 바코드 이미지 생성을 위한 BarcodeGenerator.

BarcodeGenerator 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| BarcodeGenerator(type) | BarcodeGenerator 클래스의 새 인스턴스를 초기화합니다 |
| BarcodeGenerator(type, code_text) | BarcodeGenerator 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| 매개변수 | 생성 매개변수. |
| barcode_type | 바코드 심볼 유형. |
| code_text | 인코딩할 텍스트. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| set_code_text(code_bytes) | 코드텍스트를 바이트 시퀀스로 설정합니다. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | 바코드 이미지를 특정 형식으로 스트림에 저장합니다. |
| save(filename, format) | 바코드 이미지를 특정 형식의 파일에 저장합니다. |
| save(filename) | 바코드 이미지를 특정 형식의 파일에 저장합니다. |
| export_to_xml(xml_file) | 지정된 xml 파일에 BarCode 속성을 내보냅니다. |
| export_to_xml(xml) | 지정된 xml 스트림에 BarCode 속성을 내보냅니다. |
| import_from_xml(xml_file) | 지정된 xml 파일에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다. |
| import_from_xml(xml) | 지정된 xml 스트림에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다. |
| generate_bar_code_image() | 현재 설정으로 바코드 이미지를 생성합니다. |

### 또 보기

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

