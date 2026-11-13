---
title: "BarCodeReader"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 이를 통해 바코드를 감지하기 위해 ReadBarCodes 작업을 수행할 수 있습니다.

BarCodeReader 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| BarCodeReader() | 기본값으로 [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 클래스를 새 인스턴스로 초기화합니다.<br/>            ReadBarCodes() 메서드를 호출하기 전에 이미지(SetBitmapImage())를 설정해야 합니다. |
| BarCodeReader(image) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(image, decode_types) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(image, type) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(image, area, decode_types) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(image, area, type) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(image, areas, decode_types) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(image, areas, type) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(filename) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(filename, decode_types) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(filename, type) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(stream) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(stream, type) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(stream, decode_types) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(frame, areas, type) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(frame, areas, decode_types) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(frame, area, type) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(frame, area, decode_types) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(frame, type) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(frame, decode_types) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
| BarCodeReader(frame) | BarCodeReader 클래스를 새 인스턴스로 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| processor_settings | 프로세서 코어 사용에 대한 설정을 가져옵니다. |
| timeout | 인식 프로세스의 타임아웃을 밀리초 단위로 가져오거나 설정합니다. |
| found_bar_codes | 인식된 [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) 배열을 가져옵니다 |
| found_count | 인식된 바코드 수를 가져옵니다 |
| quality_settings | QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다.<br/>            내장 프리셋인 HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes를 사용하여 QualitySettings를 빠르게 설정할 수 있거나, 개별 옵션을 수동으로 구성할 수 있습니다.<br/>            QualitySettings의 기본값은 NormalQuality입니다. |
| barcode_settings | 주요 BarCode 디코딩 매개변수입니다. 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| bar_code_read_type | 인식에 사용되는 바코드 디코드 유형을 가져오거나 설정합니다.<br/>            [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/)을 호출하기 전에 설정해야 합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| set_bar_code_image(value) | 인식을 위한 비트맵 이미지를 설정합니다. <br/>            ReadBarCodes() 메서드 호출 전에 호출해야 합니다. |
| set_bar_code_image(value, areas) | 인식을 위한 비트맵 이미지와 영역을 설정합니다. <br/>            ReadBarCodes() 메서드 호출 전에 호출해야 합니다. |
| set_bar_code_image(value, area) | 인식을 위한 비트맵 이미지와 영역을 설정합니다. <br/>            ReadBarCodes() 메서드 호출 전에 호출해야 합니다. |
| set_bar_code_image(filename) | 인식을 위한 이미지 파일을 설정합니다. <br/>            ReadBarCodes() 메서드 호출 전에 호출해야 합니다. |
| set_bar_code_image(stream) | 인식을 위한 이미지 스트림을 설정합니다. <br/>            ReadBarCodes() 메서드 호출 전에 호출해야 합니다. |
| set_bar_code_image(frame, area) | 인식을 위한 광도 프레임과 영역을 설정합니다. [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 메서드 호출 전에 호출해야 합니다. |
| set_bar_code_image(frame, areas) | 인식을 위한 광도 프레임과 영역들을 설정합니다. [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 메서드 호출 전에 호출해야 합니다. |
| set_bar_code_image(frame) | 인식을 위한 광도 프레임과 영역을 설정합니다. [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) 메서드 호출 전에 호출해야 합니다. |
| export_to_xml(xml_file) | 지정된 xml 파일에 BarCode 속성을 내보냅니다. |
| export_to_xml(xml_stream) | 지정된 xml 스트림에 BarCode 속성을 내보냅니다. |
| import_from_xml(xml_file) | 지정된 xml 파일에서 BarCode 속성을 가져와 현재 BarCodeReader 인스턴스에 적용합니다. |
| import_from_xml(xml_stream) | 지정된 xml 스트림에서 BarCode 속성을 가져와 현재 BarCodeReader 인스턴스에 적용합니다. |
| abort() | 이 함수는 다른 스레드에서 현재 인식 세션의 종료를 요청합니다. Abort는 차단할 수 없는 메서드이며 호출 직후 제어권을 반환합니다. <br/>            인식 과정이 너무 오래 걸릴 때 이 메서드를 사용해야 합니다. |
| read_bar_codes() | 이미지에서 [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)를 읽습니다. |
| set_bar_code_read_type(barcode_types) | 인식용으로 [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) 유형 배열을 설정합니다. <br/>            ReadBarCodes() 메서드 호출 전에 반드시 호출되어야 합니다. |

### 또 보기

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

