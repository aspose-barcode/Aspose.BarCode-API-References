---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Pdf417Parameters 속성. 매크로 문자 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻기 위해 사용됩니다. MicroPdf417와만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값은 MacroCharacters.None"
type: docs
weight: 90
url: /ko/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Macro Characters 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417에서만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## 예제

이 샘플은 MicroPdf417에서 매크로 문자를 인코딩하는 방법을 보여줍니다

```csharp
[C#]
//05 매크로를 사용하여 MicroPdf417를 인코딩합니다. 문자열: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//06 매크로를 사용하여 MicroPdf417를 인코딩합니다. 문자열: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### 또 보기

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


