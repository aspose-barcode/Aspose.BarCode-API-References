---
title: "Aspose::BarCode::Generation::DotCodeParameters class"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::DotCodeParameters class. C++에서 DotCode 매개변수."
type: docs
weight: 2200
url: /ko/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


DotCode 매개변수.

```cpp
class DotCodeParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [get_Columns](./get_columns/)() const | 열 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 열 수는 최소 5이어야 합니다. 기본값: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI 인코딩을 식별합니다. DotCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | DotCode 인코드 모드를 식별합니다. 기본값: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 코드가 바코드 리더기의 초기화 또는 재프로그램을 위한 지시로 다음 데이터를 해석하도록 리더기에 사용되는지 여부를 나타냅니다. 기본값은 false입니다. |
| [get_Rows](./get_rows/)() const | 행 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 행 수는 최소 5이어야 합니다. 기본값: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | DotCode 구조 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | DotCode 구조 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 수는 1에서 35 사이여야 합니다. |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [set_Columns](./set_columns/)(int32_t) | 열 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 열 수는 최소 5이어야 합니다. 기본값: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI 인코딩을 식별합니다. DotCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | DotCode 인코드 모드를 식별합니다. 기본값: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | 코드가 바코드 리더기의 초기화 또는 재프로그램을 위한 지시로 다음 데이터를 해석하도록 리더기에 사용되는지 여부를 나타냅니다. 기본값은 false입니다. |
| [set_Rows](./set_rows/)(int32_t) | 행 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 행 수는 최소 5이어야 합니다. 기본값: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | DotCode 구조 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | DotCode 구조 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 수는 1에서 35 사이여야 합니다. |
| [ToString](./tostring/)() const override | 이 [DotCodeParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
