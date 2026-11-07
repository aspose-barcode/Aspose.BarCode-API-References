---
title: "Aspose::BarCode::Generation::DataMatrixParameters 클래스"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::DataMatrixParameters 클래스. C++의 DataMatrix 매개변수입니다."
type: docs
weight: 2000
url: /ko/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


DataMatrix 매개변수.

```cpp
class DataMatrixParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [get_EccType](./get_ecctype/)() const | Datamatrix ECC 유형을 가져옵니다. 기본값: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI 인코딩을 가져옵니다. EncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Datamatrix 바코드의 인코드 모드입니다. 기본값: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. 기본값: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro Characters 05 및 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. [DataMatrixEccType.Ecc200](../datamatrixecctype/) 또는 [DataMatrixEccType.EccAuto](../datamatrixecctype/)와만 사용할 수 있습니다. [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/)와는 사용할 수 없습니다. 기본값: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Datamatrix 바코드의 구조화 추가 모드에 대한 바코드 ID입니다. 기본값: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Datamatrix 바코드의 구조화 추가 모드에 대한 바코드 수입니다. 기본값: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. 기본값: 0 |
| [get_Version](./get_version/)() const | Datamatrix 심볼 크기를 가져옵니다. 기본값: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Datamatrix ECC 유형을 설정합니다. 기본값: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI 인코딩을 설정합니다. EncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Datamatrix 바코드의 인코드 모드입니다. 기본값: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. 기본값: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro Characters 05 및 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. [DataMatrixEccType.Ecc200](../datamatrixecctype/) 또는 [DataMatrixEccType.EccAuto](../datamatrixecctype/)와만 사용할 수 있습니다. [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/)와는 사용할 수 없습니다. 기본값: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Datamatrix 바코드의 구조화 추가 모드에 대한 바코드 ID입니다. 기본값: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Datamatrix 바코드의 구조화 추가 모드에 대한 바코드 수입니다. 기본값: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Datamatrix 바코드의 Structured Append 모드에 대한 파일 ID. 기본값: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Datamatrix 심볼 크기를 설정합니다. 기본값: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | 이 [DataMatrixParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
