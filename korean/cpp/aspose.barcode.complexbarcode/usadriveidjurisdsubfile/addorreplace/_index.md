---
title: "메서드"
linktitle: "AddOrReplace"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "메서드. C++에서 ElementID가 이미 존재하면 새 DataElement를 추가하거나 교체합니다."
type: docs
weight: 800
url: /ko/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/addorreplace/
---
## USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) method


새 **DataElement**를 추가하거나 ElementID가 이미 존재하면 교체합니다.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 노드 | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | 추가할 **DataElement** |

### ReturnValue

추가/교체된 데이터 요소

## 또 보기

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## USADriveIdJurisdSubfile::AddOrReplace(System::String, System::String) method


지정된 식별자와 값을 가진 새 **DataElement**를 추가하거나, 동일한 ElementID를 가진 항목이 이미 존재하면 기존 요소를 교체합니다.

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::String id, System::String value)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| id | System::String | 관할 관련 데이터 요소를 고유하게 지정하는 3자리 식별자. |
| 값 | System::String | 데이터 요소에 할당된 텍스트 값; 요소가 이미 존재하면 이 값이 기존 값을 덮어씁니다. |

### ReturnValue

컬렉션에 추가되었거나 제자리에서 업데이트된 **DataElement** 인스턴스.

## 또 보기

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
