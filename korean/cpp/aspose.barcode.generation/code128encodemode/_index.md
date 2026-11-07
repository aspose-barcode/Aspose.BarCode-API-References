---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " enum. Code128 바코드의 인코딩 모드. C++의 Code 128 사양."
type: docs
weight: 5900
url: /ko/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Code128 바코드의 인코딩 모드. Code 128

사양.

```cpp
enum class Code128EncodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 자동 | 0 | 코드 텍스트를 클래식 ISO 15417 모드로 인코딩합니다. 이 모드는 모든 일반적인 경우에 사용해야 합니다. |
| CodeA | 1 | 코드 텍스트를 128A 코드셋으로만 인코딩합니다. |
| CodeB | 2 | 코드 텍스트를 128B 코드셋으로만 인코딩합니다. |
| CodeC | 4 | 코드 텍스트를 128C 코드셋으로만 인코딩합니다. |
| CodeAB | 3 | 코드 텍스트를 128A 및 128B 코드셋으로만 인코딩합니다. |
| CodeAC | 5 | 코드 텍스트를 128A 및 128C 코드셋으로만 인코딩합니다. |
| CodeBC | 6 | 코드 텍스트를 128B 및 128C 코드셋으로만 인코딩합니다. |

## 비고


이 코드는 다양한 인코딩으로 코드 128을 생성하는 방법을 보여줍니다.
```cpp
[C#]
//ISO 15417 인코딩으로 코드 128을 생성합니다.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//코드 128을 코드셋 A 인코딩으로만 생성합니다.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
