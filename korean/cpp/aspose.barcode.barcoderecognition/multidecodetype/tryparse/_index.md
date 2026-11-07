---
title: "메서드"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 C++에서 나타냅니다."
type: docs
weight: 1100
url: /ko/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


[MultiDecodeType](../)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parsingType | System::String | 변환을 위한 문자열 형식으로 "AllSupportedTypes" 또는 "EAN8,EAN13,CodaBar" 중 하나입니다. |
| result | System::SharedPtr\<MultiDecodeType\>\& | 변환이 성공적으로 완료되면 실제 [MultiDecodeType](../)이 반환됩니다; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## 비고



그렇지 않으면 불확정 유형을 반환합니다.

또는 [MultiDecodeType](../) ("None").

## 또 보기

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
