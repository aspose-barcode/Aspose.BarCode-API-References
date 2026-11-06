---
title: "enum"
linktitle: "MaxiCodeEncodeMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "تعداد. وضع الترميز لباركودات MaxiCode في C++."
type: docs
weight: 7500
url: /ar/cpp/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enum


وضع الترميز لباركودات MaxiCode.

```cpp
enum class MaxiCodeEncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | في وضع Auto، يتم ترميز CodeText بأقصى ضغط للبيانات. تُعاد ترميز أحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. |
| ممتد | 3 |  |
| ثنائي | 4 | في وضع الثنائي، يتم ترميز CodeText بأقصى ضغط للبيانات. إذا تم العثور على حرف Unicode، يتم رفع استثناء. |
| ECI | 5 | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. يرجى ملاحظة أن بعض الماسحات (قبل 2006) قد لا تدعم هذا الوضع. |

## ملاحظات



```cpp
[C#]
//وضع Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//وضع Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//وضع النص المشفر الموسع
//إنشاء نص مشفر
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//توليد نص مشفر
string codetext = textBuilder.GetExtendedCodetext();

//توليد
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
