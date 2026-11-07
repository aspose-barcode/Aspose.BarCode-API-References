---
title: "Aspose::BarCode::Generation::AztecParameters 클래스"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::AztecParameters 클래스. C++에서 Aztec 매개변수."
type: docs
weight: 300
url: /ko/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec 매개변수.

```cpp
class AztecParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI 인코딩을 가져옵니다. AztecEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Aztec 인코드 모드를 가져옵니다. 기본값: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [get_LayersCount](./get_layerscount/)() const | Aztec 심볼의 레이어 수를 가져옵니다. 레이어 수는 Compact 모드에서는 1에서 3 사이, Full Range 모드에서는 1에서 32 사이여야 합니다. 기본값: 0 (자동). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec 바코드의 Structured Append 모드에 대한 바코드 ID입니다. 바코드 ID는 1에서 바코드 수 사이여야 합니다. 기본값: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec 바코드의 Structured Append 모드에 대한 바코드 수입니다. 바코드 수는 1에서 26 사이여야 합니다. 기본값: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec 바코드의 Structured Append 모드에 대한 파일 ID(선택 필드)입니다. 파일 ID에는 공백이 포함될 수 없습니다. 기본값: 빈 문자열 |
| [get_SymbolMode](./get_symbolmode/)() const | Aztec Symbol 모드를 가져옵니다. 기본값: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI 인코딩을 설정합니다. AztecEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Aztec 인코드 모드를 설정합니다. 기본값: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Aztec 심볼의 레이어 수를 설정합니다. 레이어 수는 Compact 모드에서는 1에서 3 사이, Full Range 모드에서는 1에서 32 사이여야 합니다. 기본값: 0 (자동). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Aztec 바코드의 Structured Append 모드에 대한 바코드 ID입니다. 바코드 ID는 1에서 바코드 수 사이여야 합니다. 기본값: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Aztec 바코드의 Structured Append 모드에 대한 바코드 수입니다. 바코드 수는 1에서 26 사이여야 합니다. 기본값: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Aztec 바코드의 Structured Append 모드에 대한 파일 ID(선택 필드)입니다. 파일 ID에는 공백이 포함될 수 없습니다. 기본값: 빈 문자열 |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Aztec Symbol 모드를 설정합니다. 기본값: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | 이 [AztecParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
