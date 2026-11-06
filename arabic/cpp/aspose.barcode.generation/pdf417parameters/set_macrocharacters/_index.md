---
title: "طريقة"
linktitle: "set_MacroCharacters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "طريقة. تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر تكثيفًا في أوضاع خاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع MicroPdf417 916 و917. القيمة الافتراضية: MacroCharacters.None في C++."
type: docs
weight: 4000
url: /ar/cpp/aspose.barcode.generation/pdf417parameters/set_macrocharacters/
---
## Pdf417Parameters::set_MacroCharacters method


تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر تكثيفًا في أوضاع خاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع MicroPdf417 916 و917. القيمة الافتراضية: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_MacroCharacters(MacroCharacter value)
```

## ملاحظات


تُظهر هذه الأمثلة كيفية ترميز الأحرف الماكرو في MicroPdf417
```cpp
[C#]
//يقوم بترميز MicroPdf417 باستخدام ماكرو 05 السلسلة: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//يقوم بترميز MicroPdf417 باستخدام ماكرو 06 السلسلة: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## انظر أيضًا

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
