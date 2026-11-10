---
title: "تعداد AztecEncodeMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "تعداد Aspose.BarCode.Generation.AztecEncodeMode. وضع الترميز لباركودات Aztec"
type: docs
weight: 940
url: /ar/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

وضع الترميز لباركودات Aztec.

```csharp
public enum AztecEncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. يتم إعادة ترميز الأحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المختار، يتم إلقاء استثناء. |
| Extended | `3` | الوضع الموسع الذي يدعم أوضاع ECI المتعددة. |
| Binary | `4` | في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. إذا تم العثور على حرف Unicode، يتم إلقاء استثناء. |
| ECI | `5` | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المختار، يتم إلقاء استثناء. يرجى ملاحظة أن بعض الماسحات الضوئية القديمة (قبل 2006) قد لا تدعم هذا الوضع. |

## أمثلة

```csharp
[C#]
//وضع Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//وضع Extended
//إنشاء نص شيفرة.
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//توليد نص شيفرة.
string codetext = textBuilder.GetExtendedCodetext();    

//توليد.
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### انظر أيضًا

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


