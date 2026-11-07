---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext 클래스"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext 클래스. C++에서 Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스입니다."
type: docs
weight: 1400
url: /ko/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Class](./get_class/)() const | 항목의 클래스를 식별합니다. |
| [get_CustomerContent](./get_customercontent/)() const | 고객이 사용할 수 있는 선택적 공간입니다. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Datamatrix 바코드의 인코드 모드입니다. 기본값: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | 배송 [Address](../address/)의 우편번호와 DPS를 포함합니다. 내륙인 경우 우편번호/DP는 다음과 같은 문자 수를 가집니다. 지역(1~2자) 구역(1~2자) 섹터(1자) 유닛(2자) DPS(2자). 우편번호와 DPS는 유효한 PAF® 형식이어야 합니다. |
| [get_InformationTypeID](./get_informationtypeid/)() const | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. |
| [get_ItemID](./get_itemid/)() const | 공급망 ID 내에서 고유한 항목을 식별합니다. 모든 Mailmark 바코드에는 최소 90일 동안 고유하게 식별될 수 있도록 ID가 포함되어야 합니다. 최대값: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | 반송용 우편번호를 포함하지만 DPS는 포함하지 않습니다. DPS가 없는 PC는 PAF® 형식이어야 합니다. |
| [get_RTSFlag](./get_rtsflag/)() const | 요청된 반송 서비스 수준을 나타내는 플래그입니다. |
| [get_SupplyChainID](./get_supplychainid/)() const | 우편 발송에 관여하는 고유한 고객 그룹을 식별합니다. 최대값: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
| [get_VersionID](./get_versionid/)() const | 각 정보 유형 ID와 관련된 바코드 버전을 식별합니다. |
| [GetBarcodeType](./getbarcodetype/)() override | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Mailmark 데이터에서 코드텍스트를 구성합니다. |
| [InitFromString](./initfromstring/)(System::String) override | 구성된 코드텍스트에서 Mailmark 데이터를 초기화합니다. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | 생성자. 기본 [Mailmark2DCodetext](./) 클래스 인스턴스를 생성합니다. |
| [set_Class](./set_class/)(System::String) | 항목의 클래스를 식별합니다. |
| [set_CustomerContent](./set_customercontent/)(System::String) | 고객이 사용할 수 있는 선택적 공간입니다. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Datamatrix 바코드의 인코드 모드입니다. 기본값: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | 배송 [Address](../address/)의 우편번호와 DPS를 포함합니다. 내륙인 경우 우편번호/DP는 다음과 같은 문자 수를 가집니다. 지역(1~2자) 구역(1~2자) 섹터(1자) 유닛(2자) DPS(2자). 우편번호와 DPS는 유효한 PAF® 형식이어야 합니다. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. |
| [set_ItemID](./set_itemid/)(int32_t) | 공급망 ID 내에서 고유한 항목을 식별합니다. 모든 Mailmark 바코드에는 최소 90일 동안 고유하게 식별될 수 있도록 ID가 포함되어야 합니다. 최대값: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | 반송용 우편번호를 포함하지만 DPS는 포함하지 않습니다. DPS가 없는 PC는 PAF® 형식이어야 합니다. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | 요청된 반송 서비스 수준을 나타내는 플래그입니다. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | 우편 발송에 관여하는 고유한 고객 그룹을 식별합니다. 최대값: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
| [set_VersionID](./set_versionid/)(System::String) | 각 정보 유형 ID와 관련된 바코드 버전을 식별합니다. |
## 또 보기

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
