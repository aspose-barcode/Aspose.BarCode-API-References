---
title: "메서드"
linktitle: "get_MacroCharacters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "메서드. 매크로 문자 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻기 위해 사용됩니다. MicroPdf417에서만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: MacroCharacters.None (C++)."
type: docs
weight: 3900
url: /ko/cpp/aspose.barcode.generation/pdf417parameters/get_macrocharacters/
---
## Pdf417Parameters::get_MacroCharacters method


매크로 문자 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻기 위해 사용됩니다. MicroPdf417에서만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
MacroCharacter Aspose::BarCode::Generation::Pdf417Parameters::get_MacroCharacters() const
```

## 비고


이 샘플은 MicroPdf417에서 매크로 문자를 인코딩하는 방법을 보여줍니다.
```cpp
[C#]
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

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
