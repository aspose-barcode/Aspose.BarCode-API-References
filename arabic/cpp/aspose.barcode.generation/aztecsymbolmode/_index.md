---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "enum. يحدد وضع رمز Aztec في C++."
type: docs
weight: 5400
url: /ar/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


يحدد وضع رمز Aztec.

```cpp
enum class AztecSymbolMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | يحدد اختيار الرمز الأفضل تلقائيًا (Compact أو Full-range) لـ Aztec. هذه هي القيمة الافتراضية. |
| Compact | 1 | يحدد الرمز Compact لـ Aztec. يسمح رمز Aztec Compact فقط بـ 1 أو 2 أو 3 أو 4 طبقات. |
| FullRange | 2 | يحدد الرمز Full-range لـ Aztec. يسمح رمز Aztec Full-range من 1 إلى 32 طبقة. |
| Rune | 3 | يحدد رمز Rune لـ Aztec. رموز Aztec Runes هي سلسلة من العلامات الصغيرة ولكن المميزة القابلة للقراءة آليًا. يسمح فقط بالقيمة العددية من 0 إلى 255. |

## ملاحظات


يعرض هذا المثال كيفية تغيير وضع رمز Aztec وحفظ صورة [BarCode](../../aspose.barcode/).
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
