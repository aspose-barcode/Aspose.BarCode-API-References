---
title: "메서드"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. BaseEncodeType의 문자열 표현을 인스턴스로 변환합니다. 반환값은 C++에서 변환이 성공했는지 여부를 나타냅니다."
type: docs
weight: 400
url: /ko/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


문자열 표현인 [BaseEncodeType](../../baseencodetype/)을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 여부를 나타냅니다.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parsingType | System::String | 변환할 \"Index:-1; Name:None\" 형식의 문자열. |
| result | System::SharedPtr\<BaseEncodeType\>\& | 변환이 성공적으로 완료되면 실제 SingleEncodeType이 반환됩니다; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## 비고



그렇지 않으면 null을 반환합니다.

## 또 보기

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
