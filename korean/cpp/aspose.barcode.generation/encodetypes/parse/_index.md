---
title: "메서드"
linktitle: "Parse"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. BaseEncodeType의 문자열 표현을 인스턴스로 변환합니다. 반환값은 C++에서 변환이 성공했는지 여부를 나타냅니다."
type: docs
weight: 300
url: /ko/cpp/aspose.barcode.generation/encodetypes/parse/
---
## EncodeTypes::Parse method


문자열 표현인 [BaseEncodeType](../../baseencodetype/)을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 여부를 나타냅니다.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::Parse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parsingType | System::String | [BaseEncodeType](../../baseencodetype/) 표현을 변환하기 위한 문자열을 포함합니다. |
| result | System::SharedPtr\<BaseEncodeType\>\& | 변환이 성공적으로 완료될 때 실제 [BaseEncodeType](../../baseencodetype/)을 반환합니다; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## 비고



그렇지 않으면 null을 반환합니다.

## 또 보기

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
