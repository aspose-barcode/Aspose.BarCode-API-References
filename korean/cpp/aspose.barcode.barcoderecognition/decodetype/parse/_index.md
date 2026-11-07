---
title: "메서드"
linktitle: "Parse"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. SingleDecodeType의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 C++에서 나타냅니다."
type: docs
weight: 400
url: /ko/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


 [SingleDecodeType](../../singledecodetype/)의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parsingType | System::String | 변환을 위해 "EAN8" 또는 "EAN13" 또는 "CodaBar" 형식의 [SingleDecodeType](../../singledecodetype/)을 포함하는 문자열. |
| result | System::SharedPtr\<SingleDecodeType\>\& | 실제 [SingleDecodeType](../../singledecodetype/)은 변환이 성공적으로 완료되면 반환됩니다; 그렇지 않으면 불확정 유형인 [DecodeType.None](../none/)을 반환합니다. |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 또 보기

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
