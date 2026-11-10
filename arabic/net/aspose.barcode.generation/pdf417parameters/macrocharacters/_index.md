---
title: "Pdf417Parameters.MacroCharacters"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "خاصية Pdf417Parameters. تُستخدم قيم Macro Characters 05 و06 للحصول على ترميز أكثر كثافة في أوضاع خاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع 916 و917 لـ MicroPdf417. القيمة الافتراضية MacroCharacters.None"
type: docs
weight: 90
url: /ar/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع MicroPdf417 916 و917. القيمة الافتراضية: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## أمثلة

تُظهر هذه الأمثلة كيفية ترميز Macro Characters في MicroPdf417

```csharp
[C#]
//يقوم بترميز MicroPdf417 باستخدام Macro 05 للسلسلة: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//يقوم بترميز MicroPdf417 باستخدام Macro 06 للسلسلة: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### انظر أيضًا

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


