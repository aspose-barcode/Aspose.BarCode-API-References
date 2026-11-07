---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext 클래스"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext 클래스. C++에서 4단계 Royal Mailmark 코드에 삽입된 텍스트를 인코딩하고 디코드하기 위한 클래스입니다."
type: docs
weight: 1500
url: /ko/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


4-state Royal Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Null 또는 테스트 "1" - 1C (소매) "2" - 2C (소매) "3" - 3C (소매) "4" - 프리미엄 (RetailPublishing Mail) (향후 사용 가능) "5" - 연기 (소매) "6" - 항공 (소매) (향후 사용 가능) "7" - 표면 (소매) (향후 사용 가능) "8" - 프리미엄 (네트워크 액세스) "9" - 표준 (네트워크 액세스) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC와 DP는 PAF 형식을 따라야 합니다. 국제 코드를 나타내는 9자 문자열 "XY11     " (뒤에 공백 5개 포함) 또는 국내 정렬 코드를 나타내는 문자 패턴 중 하나입니다. 국내 정렬 코드는 외부 우편번호, 내부 우편번호 및 Delivery Point Suffix로 구성됩니다. |
| [get_Format](./get_format/)() const | "0" – Null 또는 테스트 "1" – 편지 "2" – 대형 편지 |
| [get_ItemID](./get_itemid/)() const | 최대 값은 99999999입니다. |
| [get_SupplychainID](./get_supplychainid/)() const | Barcode C의 최대 값은 99이고 Barcode L의 최대 값은 999999입니다. |
| [get_VersionID](./get_versionid/)() const | 현재 "1" – Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 예비) |
| [GetBarcodeType](./getbarcodetype/)() override | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Mailmark 데이터에서 코드텍스트를 구성합니다. |
| [InitFromString](./initfromstring/)(System::String) override | 구성된 코드텍스트에서 Mailmark 데이터를 초기화합니다. |
| [MailmarkCodetext](./mailmarkcodetext/)() | 새로운 [MailmarkCodetext](./) 클래스 인스턴스를 초기화합니다. |
| [set_Class](./set_class/)(System::String) | "0" - Null 또는 테스트 "1" - 1C (소매) "2" - 2C (소매) "3" - 3C (소매) "4" - 프리미엄 (RetailPublishing Mail) (향후 사용 가능) "5" - 연기 (소매) "6" - 항공 (소매) (향후 사용 가능) "7" - 표면 (소매) (향후 사용 가능) "8" - 프리미엄 (네트워크 액세스) "9" - 표준 (네트워크 액세스) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC와 DP는 PAF 형식을 따라야 합니다. 국제 코드를 나타내는 9자 문자열 "XY11     " (뒤에 공백 5개 포함) 또는 국내 정렬 코드를 나타내는 문자 패턴 중 하나입니다. 국내 정렬 코드는 외부 우편번호, 내부 우편번호 및 Delivery Point Suffix로 구성됩니다. |
| [set_Format](./set_format/)(int32_t) | "0" – Null 또는 테스트 "1" – 편지 "2" – 대형 편지 |
| [set_ItemID](./set_itemid/)(int32_t) | 최대 값은 99999999입니다. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Barcode C의 최대 값은 99이고 Barcode L의 최대 값은 999999입니다. |
| [set_VersionID](./set_versionid/)(int32_t) | 현재 "1" – Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 예비) |
## 또 보기

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
