---
title: "عدد DotCodeEncodeMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "عدد Aspose.BarCode.Generation.DotCodeEncodeMode. وضع الترميز لباركودات DotCode"
type: docs
weight: 1240
url: /ar/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

وضع الترميز لباركودات DotCode.

```csharp
public enum DotCodeEncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. يتم إعادة ترميز الأحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المختار، يتم إلقاء استثناء. |
| Binary | `3` | في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. إذا تم العثور على حرف Unicode، يتم إلقاء استثناء. |
| ECI | `4` | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المختار، يتم إلقاء استثناء. يرجى ملاحظة أن بعض الماسحات الضوئية القديمة (قبل 2006) قد لا تدعم هذا الوضع. |
| Extended | `5` | الوضع الموسع الذي يدعم أوضاع ECI المتعددة. |

## أمثلة

```csharp
[C#]
//الوضع التلقائي مع الماكرو
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

//وضع النص الشيفري الموسع.
//إنشاء نص شيفرة.
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//توليد نص شيفرة.
string codetext = textBuilder.GetExtendedCodetext();    

//توليد.
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### انظر أيضًا

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


