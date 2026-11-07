---
title: "메서드"
linktitle: "생성"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. C++에서 GS1 codetext의 모든 요소를 복사하고 유일한 기본 키를 선택하여 GS1 Digital Link를 생성합니다."
type: docs
weight: 2100
url: /ko/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


GS1 코드 텍스트의 모든 요소를 복사하고 사용 가능한 유일한 기본 키를 선택하여 GS1 Digital Link를 생성합니다.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uriStem | System::String | 기본 키 앞의 절대 HTTP 또는 HTTPS URI 접두사. |
| codetext | System::SharedPtr\<GS1Codetext\> | 요소가 복사되는 GS1 codetext. |

### ReturnValue

복사된 요소를 포함하는 GS1 디지털 링크.

## 또 보기

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


GS1 코드 텍스트의 모든 요소를 복사하고 지정된 기본 키를 사용하여 GS1 Digital Link를 생성합니다.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uriStem | System::String | 기본 키 앞의 절대 HTTP 또는 HTTPS URI 접두사. |
| codetext | System::SharedPtr\<GS1Codetext\> | 요소가 복사되는 GS1 codetext. |
| primaryApplicationIdentifier | System::String | 기본 키 AI. |

### ReturnValue

복사된 요소를 포함하는 GS1 디지털 링크.

## 또 보기

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
