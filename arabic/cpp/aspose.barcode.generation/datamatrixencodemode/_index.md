---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "enum. وضع الترميز لمشفّر DataMatrix، الافتراضي Auto في C++."
type: docs
weight: 6300
url: /ar/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


وضع الترميز لمشفّر DataMatrix، الافتراضي Auto

```cpp
enum class DataMatrixEncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | في وضع Auto، يتم ترميز CodeText بأقصى ضغط للبيانات. تُعاد ترميز أحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. |
| ASCII | 1 | يقوم بترميز حرف أبجدي رقمي واحد أو رقمين لكل بايت |
| C40 | 8 | يستخدم ترميز C40. يقوم بترميز الأحرف الأبجدية الرقمية الكبيرة، الأحرف الصغيرة والرموز الخاصة. |
| نص | 9 | يستخدم ترميز Text. يقوم بترميز الأحرف الأبجدية الرقمية الصغيرة، الأحرف الكبيرة والرموز الخاصة. |
| EDIFACT | 10 | يستخدم ترميز EDIFACT. يستخدم ست بتات لكل حرف، يرمّز الأرقام، الأحرف الكبيرة، والعديد من علامات الترقيم، لكنه لا يدعم الأحرف الصغيرة. |
| ANSIX12 | 11 | يستخدم ترميز ANSI X12. |
| ممتد | 13 |  |
| Base256 | 14 | ترميز قيم 8 بت |
| ثنائي | 15 | في وضع الثنائي، يتم ترميز CodeText بأقصى ضغط للبيانات. إذا تم العثور على حرف Unicode، يتم رفع استثناء. |
| ECI | 16 | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. يرجى ملاحظة أن بعض الماسحات (قبل 2006) قد لا تدعم هذا الوضع. |

## ملاحظات


يعرض هذا المثال كيفية تنفيذ codetext في وضع الممتد.
```cpp
[C#]
//وضع Auto
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//وضع Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//وضع النص المشفر الموسع
//إنشاء نص مشفر
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//توليد نص مشفر
string codetext = textBuilder.GetExtendedCodetext();

//توليد
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
