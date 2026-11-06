---
title: "طريقة"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. اضبط codetext كسلسلة من البايتات في C++."
type: docs
weight: 700
url: /ar/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


عيّن نص الرمز كسلسلة من البايتات.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | بايتات codetext |

## انظر أيضًا

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| codeText | System::String | سلسلة CodeText |
| الترميز | System::SharedPtr\<System::Text::Encoding\> | الترميز المطبق |
## ملاحظات


يقوم بترميز النص Unicode **codeText** إلى تسلسل بايتات باستخدام **encoding** المحدد. UTF-8 هو الترميز الأكثر استخدامًا. إذا كان الترميز يدعم ذلك، فإن الدالة تُدرج تلقائيًا علامة ترتيب البايتات (BOM) [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

هذه الدالة مخصصة للاستخدام مع الباركود ثنائي الأبعاد فقط (مثل Aztec، QR، DataMatrix، PDF417، MaxiCode، DotCode، HanXin، RectMicroQR، وغيرها). تتيح ترميز يدوي لنص Unicode باستخدام الترميزات الوطنية أو الخاصة؛ ومع ذلك، يُعتبر هذا الأسلوب قديمًا في التطبيقات الحديثة. للحالات الحديثة، يُنصح باستخدام ترميز [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) لبيانات Unicode.

استخدام هذه الدالة مع باركود أحادي الأبعاد، أو باركود متوافق مع GS1 (بما في ذلك ثنائي الأبعاد)، أو باركود HIBC (بما في ذلك ثنائي الأبعاد) غير مدعوم من قبل معايير الباركود المقابلة وقد يؤدي إلى نتائج غير متوقعة.


يوضح هذا المثال كيفية استخدام **SetCodeText** لتعيين نص مشفر بـ Unicode للباركود ثنائي الأبعاد باستخدام ترميزات مختلفة:


```cpp
[C#]
//ترميز نص QR Code باستخدام UTF-8 مع BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //ترميز نص DataMatrix باستخدام Shift-JIS (ترميز ياباني)
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## انظر أيضًا

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| codeText | System::String | سلسلة CodeText |
| الترميز | System::SharedPtr\<System::Text::Encoding\> | الترميز المطبق |
| insertBOM | bool | يشير إلى ما إذا كان يجب إدراج علامة ترتيب البايتات (BOM) عندما يدعم الترميز المحدد ذلك (مثل UTF-8، UTF-16، UTF-32). إذا تم تعيينه إلى **true**, تُضاف الـ BOM؛ إذا تم تعيينه إلى **false**, تُحذف الـ BOM حتى لو كان الترميز يستخدمها عادةً. |
## ملاحظات


يقوم بترميز النص Unicode **codeText** إلى تسلسل بايتات باستخدام **encoding** المحدد. UTF-8 هو الترميز الأكثر استخدامًا. إذا كان الترميز يدعم ذلك وتم تعيين **insertBOM** إلى **true**, فإن الدالة تتضمن علامة ترتيب البايتات (BOM) [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

هذه الدالة مخصصة للاستخدام مع الباركود ثنائي الأبعاد فقط (مثل Aztec، QR، DataMatrix، PDF417، MaxiCode، DotCode، HanXin، RectMicroQR، وغيرها). تتيح ترميز يدوي لنص Unicode باستخدام الترميزات الوطنية أو الخاصة؛ ومع ذلك، يُعتبر هذا الأسلوب قديمًا في التطبيقات الحديثة. للحالات الحديثة، يُنصح باستخدام ترميز [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) لبيانات Unicode.

استخدام هذه الدالة مع باركود أحادي الأبعاد، أو باركود متوافق مع GS1 (بما في ذلك ثنائي الأبعاد)، أو باركود HIBC (بما في ذلك ثنائي الأبعاد) غير مدعوم من قبل معايير الباركود المقابلة وقد يؤدي إلى نتائج غير متوقعة.


يوضح هذا المثال كيفية استخدام **SetCodeText** مع أو بدون BOM للباركود ثنائي الأبعاد.


```cpp
[C#]
    //ترميز نص الكود باستخدام UTF-8 مع BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //ترميز نص الكود باستخدام UTF-8 بدون BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## انظر أيضًا

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
