---
title: "enum"
linktitle: "DotCodeEncodeMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "enum. وضع الترميز لباركودات DotCode في C++."
type: docs
weight: 6500
url: /ar/cpp/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enum


وضع الترميز لباركودات DotCode.

```cpp
enum class DotCodeEncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | في وضع Auto، يتم ترميز CodeText بأقصى ضغط للبيانات. تُعاد ترميز أحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. |
| ثنائي | 3 | في وضع الثنائي، يتم ترميز CodeText بأقصى ضغط للبيانات. إذا تم العثور على حرف Unicode، يتم رفع استثناء. |
| ECI | 4 | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. يرجى ملاحظة أن بعض الماسحات (قبل 2006) قد لا تدعم هذا الوضع. |
| ممتد | 5 |  |

## ملاحظات



```cpp
[C#]
//الوضع التلقائي مع الماكروهات
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//وضع Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//وضع Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//وضع النص المشفر الموسع
//إنشاء نص مشفر
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//توليد نص مشفر
string codetext = textBuilder.GetExtendedCodetext();

//توليد
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
