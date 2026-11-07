---
title: "메서드"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. SingleDecodeType의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 C++에서 나타냅니다."
type: docs
weight: 400
url: /ko/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


 [SingleDecodeType](../../singledecodetype/)의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parsingType | System::String | 변환을 위해 "EAN8" 또는 "EAN13" 또는 "CodaBar" 형식의 [SingleDecodeType](../../singledecodetype/)을 포함하는 문자열. |
| result | System::SharedPtr\<SingleDecodeType\>\& | 변환이 성공적으로 완료되면 실제 [SingleDecodeType](../../singledecodetype/)이 반환됩니다; 그렇지 않으면 불확정 타입인 [DecodeType.None](../../decodetype/none/)을 반환합니다. |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 또 보기

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


 [MultiDecodeType](../../multidecodetype/)의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parsingType | System::String | 변환을 위한 [MultiDecodeType](../../multidecodetype/) 표현을 포함하는 문자열. |
| result | System::SharedPtr\<MultiDecodeType\>\& | 변환이 성공적으로 완료되면 실제 [MultiDecodeType](../../multidecodetype/)이 반환됩니다; 그렇지 않으면 불확정 타입인 new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/))을 반환합니다. |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 또 보기

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


구체적인 타입을 결정한 후, [BaseDecodeType](../)의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parsingType | System::String | 변환을 위한 [MultiDecodeType](../../multidecodetype/) 표현을 포함하는 문자열. |
| result | System::SharedPtr\<BaseDecodeType\>\& | 변환이 성공적으로 완료되면 실제 [MultiDecodeType](../../multidecodetype/)이 반환됩니다; 그렇지 않으면 불확정 타입인 [DecodeType.None](../../decodetype/none/)을 반환합니다. |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 또 보기

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
