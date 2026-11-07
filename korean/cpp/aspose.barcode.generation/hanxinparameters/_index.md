---
title: "Aspose::BarCode::Generation::HanXinParameters class"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::HanXinParameters 클래스. C++의 Han Xin 매개변수."
type: docs
weight: 2900
url: /ko/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Han Xin 매개변수.

```cpp
class HanXinParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | 확장 채널 해석 식별자. 이는 바코드 리더에게 심볼 내 데이터 인코딩에 사용된 참조에 대한 세부 정보를 전달하는 데 사용됩니다. 현재 구현에는 알려진 모든 문자 집합 인코딩이 포함되어 있습니다. |
| [get_EncodeMode](./get_encodemode/)() const | HanXin 인코딩 모드. 기본값: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Han Xin 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: L1, L2, L3, L4. ErrorLevel을 참조하십시오. |
| [get_Version](./get_version/)() const | HanXin 코드 버전. Han Xin 코드의 경우 Version01부터 Version84까지. 기본값은 [Version.Auto](../aztecencodemode/)입니다. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 확장 채널 해석 식별자. 이는 바코드 리더에게 심볼 내 데이터 인코딩에 사용된 참조에 대한 세부 정보를 전달하는 데 사용됩니다. 현재 구현에는 알려진 모든 문자 집합 인코딩이 포함되어 있습니다. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | HanXin 인코딩 모드. 기본값: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Han Xin 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: L1, L2, L3, L4. ErrorLevel을 참조하십시오. |
| [set_Version](./set_version/)(HanXinVersion) | HanXin 코드 버전. Han Xin 코드의 경우 Version01부터 Version84까지. 기본값은 [Version.Auto](../aztecencodemode/)입니다. |
| [ToString](./tostring/)() const override | 이 [HanXinParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
