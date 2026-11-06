---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " enum. تُستخدم قيم رموز ماكرو 05 و06 للحصول على ترميز أكثر كثافة في الأنماط الخاصة. يتم ترجمة ماكرو 05 إلى \"[)>\\u001E05\\u001D\" كعنوان بيانات مُفكّك و \"\\u001E\\u0004\" كذيل بيانات مُفكّك. يتم ترجمة ماكرو 06 إلى \"[)>\\u001E06\\u001D\" كعنوان بيانات مُفكّك و \"\\u001E\\u0004\" كذيل بيانات مُفكّك في C++."
type: docs
weight: 7300
url: /ar/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


يتم استخدام قيم الأحرف الماكرو 05 و 06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. يتم ترجمة حرف الماكرو 05 إلى "[)>\u001E05\u001D" كعنوان بيانات مُفكّك و "\u001E\u0004" كذيل بيانات مُفكّك. يتم ترجمة حرف الماكرو 06 إلى "[)>\u001E06\u001D" كعنوان بيانات مُفكّك و "\u001E\u0004" كذيل بيانات مُفكّك.

```cpp
enum class MacroCharacter
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| بدون | 0 | لا يتم إضافة أي من رموز الماكرو إلى بيانات الباركود |
| Macro05 | 5 | يتم إضافة ماكرو 05 إلى بيانات الباركود في الموضع الأول. يتم ترجمة رمز معرف البيانات GS1 ISO 15434 إلى "[)>\u001E05\u001D" كعنوان بيانات مُفكّك و "\u001E\u0004" كذيل بيانات مُفكّك. |
| Macro06 | 6 | يتم إضافة ماكرو 06 إلى بيانات الباركود في الموضع الأول. يتم ترجمة رمز معرف البيانات ASC MH10 ISO 15434 إلى "[)>\u001E06\u001D" كعنوان بيانات مُفكّك و "\u001E\u0004" كذيل بيانات مُفكّك. |

## ملاحظات


تُظهر هذه العينات كيفية ترميز رموز الماكرو في MicroPdf417 وDataMatrix
```cpp
[C#]
//لإنشاء رسالة GS1 مُحددة تلقائيًا مثل هذه "(10)123ABC(10)123ABC" بصيغة ISO 15434 تحتاج إلى:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

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

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
