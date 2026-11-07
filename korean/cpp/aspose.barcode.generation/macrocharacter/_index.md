---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " enum. 매크로 문자 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. 05 매크로 문자는 디코딩된 데이터 헤더로 \"[)>\\u001E05\\u001D\" 로, 디코딩된 데이터 트레일러로 \"\\u001E\\u0004\" 로 변환됩니다. 06 매크로 문자는 디코딩된 데이터 헤더로 \"[)>\\u001E06\\u001D\" 로, 디코딩된 데이터 트레일러로 \"\\u001E\\u0004\" 로 변환되며 C++에서 사용됩니다."
type: docs
weight: 7300
url: /ko/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


특수 모드에서 더 압축된 인코딩을 얻기 위해 매크로 문자 05와 06 값을 사용합니다. 05 매크로 문자는 디코드된 데이터 헤더로 "[)>\u001E05\u001D" 로, 디코드된 데이터 트레일러로 "\u001E\u0004" 로 변환됩니다. 06 매크로 문자는 디코드된 데이터 헤더로 "[)>\u001E06\u001D" 로, 디코드된 데이터 트레일러로 "\u001E\u0004" 로 변환됩니다.

```cpp
enum class MacroCharacter
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| 없음 | 0 | 매크로 문자가 바코드 데이터에 추가되지 않습니다. |
| Macro05 | 5 | 05 매크로 문자는 첫 번째 위치에 바코드 데이터에 추가됩니다. GS1 데이터 식별자 ISO 15434 문자는 디코딩된 데이터 헤더로 "[)>\u001E05\u001D" 로, 디코딩된 데이터 트레일러로 "\u001E\u0004" 로 변환됩니다. |
| Macro06 | 6 | 06 매크로 문자는 첫 번째 위치에 바코드 데이터에 추가됩니다. ASC MH10 데이터 식별자 ISO 15434 문자는 디코딩된 데이터 헤더로 "[)>\u001E06\u001D" 로, 디코딩된 데이터 트레일러로 "\u001E\u0004" 로 변환됩니다. |

## 비고


이 샘플들은 MicroPdf417 및 DataMatrix에서 매크로 문자를 인코딩하는 방법을 보여줍니다
```cpp
[C#]
//ISO 15434 형식에서 "(10)123ABC(10)123ABC"와 같은 자동 식별 GS1 메시지를 생성하려면 다음이 필요합니다:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

//MicroPdf417를 05 매크로로 인코딩합니다 문자열: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//MicroPdf417를 06 매크로로 인코딩합니다 문자열: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
