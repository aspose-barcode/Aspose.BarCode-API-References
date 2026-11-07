---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 enum을 사용하는 방법."
type: docs
weight: 6700
url: /ko/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 기본값 | 0 | 사양에서 체크섬이 필요하면 - 체크섬이 첨부됩니다. |
| 예 | 1 | 가능하면 항상 체크섬을 사용하십시오. |
| 아니오 | 2 | 체크섬을 사용하지 마십시오. |

## 비고


1D 바코드 생성 중에 체크섬을 활성화합니다.

기본값은 체크섬이 반드시 포함되어야 하는 심볼에는 Yes로, 체크섬이 선택적인 경우 No로 처리됩니다.

체크섬이 사용되지 않음: Codabar

체크섬이 가능한 경우: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

체크섬을 항상 사용: 나머지 심볼
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
