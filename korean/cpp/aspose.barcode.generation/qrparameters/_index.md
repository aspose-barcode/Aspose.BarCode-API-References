---
title: "Aspose::BarCode::Generation::QrParameters 클래스"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::QrParameters 클래스. C++에서 QR 매개변수."
type: docs
weight: 4400
url: /ko/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR 매개변수.

```cpp
class QrParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [get_ECIEncoding](./get_eciencoding/)() const | 확장 채널 해석 식별자. 바코드 리더에게 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | QR 심볼 유형은 [BarCode](../../aspose.barcode/)의 인코딩 모드입니다. 기본값: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. 자세한 내용은 QRErrorLevel을 참조하십시오. |
| [get_MicroQRVersion](./get_microqrversion/)() const | MicroQR 코드의 버전입니다. M1 버전부터 M4 버전까지. 기본값은 [MicroQRVersion.Auto](../aztecencodemode/)입니다. |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | RectMicroQR 코드의 버전입니다. R7x59 버전부터 R17x139 버전까지. 기본값은 [RectMicroQRVersion.Auto](../aztecencodemode/)입니다. |
| [get_StructuredAppend](./get_structuredappend/)() const | QR 구조화 추가 매개변수. 구조화 추가 모드는 MicroQR 및 RectMicroQR 바코드에서 지원되지 않습니다. |
| [get_Version](./get_version/)() const | QR 코드의 버전입니다. Version1부터 Version40까지. 기본값은 [QRVersion.Auto](../aztecencodemode/)입니다. |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 확장 채널 해석 식별자. 바코드 리더에게 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | QR 심볼 유형은 [BarCode](../../aspose.barcode/)의 인코딩 모드입니다. 기본값: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. 자세한 내용은 QRErrorLevel을 참조하십시오. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | MicroQR 코드의 버전입니다. M1 버전부터 M4 버전까지. 기본값은 [MicroQRVersion.Auto](../aztecencodemode/)입니다. |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | RectMicroQR 코드의 버전입니다. R7x59 버전부터 R17x139 버전까지. 기본값은 [RectMicroQRVersion.Auto](../aztecencodemode/)입니다. |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR 구조화 추가 매개변수. 구조화 추가 모드는 MicroQR 및 RectMicroQR 바코드에서 지원되지 않습니다. |
| [set_Version](./set_version/)(QRVersion) | QR 코드의 버전입니다. Version1부터 Version40까지. 기본값은 [QRVersion.Auto](../aztecencodemode/)입니다. |
| [ToString](./tostring/)() const override | 이 [QrParameters](./)의 인간이 읽을 수 있는 문자열 표현을 반환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
