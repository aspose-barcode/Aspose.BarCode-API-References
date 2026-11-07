---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 열거형. C++에서 Pdf417 바코드 인코드 모드."
type: docs
weight: 7900
url: /ko/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Pdf417 바코드 인코드 모드

```cpp
enum class Pdf417EncodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 자동 | 0 | Auto 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. |
| 이진 | 1 | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다. |
| ECI | 2 | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있다는 점에 유의하십시오. |
| 확장 | 3 |  |

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
