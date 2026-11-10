---
title: "BarcodeGenerator.SetCodeText"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "طريقة BarcodeGenerator. اضبط codetext كسلسلة من البايتات"
type: docs
weight: 100
url: /ar/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

اضبط codetext كسلسلة من البايتات.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| codeBytes | Byte[] | بايتات codetext |

### انظر أيضًا

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

يقوم بترميز Unicode **codeText** إلى سلسلة بايتات باستخدام **encoding** المحدد. UTF-8 هو الترميز الأكثر شيوعًا. إذا كان الترميز يدعمه، فإن الدالة تُدرج تلقائيًا [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

هذه الدالة مخصصة للاستخدام مع باركودات 2D فقط (مثل Aztec، QR، DataMatrix، PDF417، MaxiCode، DotCode، HanXin، RectMicroQR، إلخ). تتيح ترميز يدوي لنص Unicode باستخدام ترميزات وطنية أو خاصة؛ ومع ذلك، تُعتبر هذه الطريقة قديمة في التطبيقات الحديثة. لحالات الاستخدام الحديثة، يُنصح باستخدام ترميز [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) لبيانات Unicode.

استخدام هذه الدالة مع باركودات 1D، أو باركودات متوافقة مع GS1 (بما في ذلك 2D)، أو باركودات HIBC (بما في ذلك 2D) غير مدعوم من قبل معايير الباركود المقابلة وقد يؤدي إلى نتائج غير متوقعة.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| codeText | String | سلسلة CodeText |
| الترميز | الترميز | الترميز المطبق |

## أمثلة

هذا المثال يوضح كيفية استخدام `SetCodeText` لتعيين نص مشفر بـ Unicode لباركودات 2D باستخدام ترميزات مختلفة:

```csharp
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

### انظر أيضًا

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

يقوم بترميز **codeText** بنظام Unicode إلى تسلسل بايتات باستخدام **encoding** المحدد. UTF-8 هو الترميز الأكثر استخدامًا. إذا كان الترميز يدعم ذلك وتم تعيين **insertBOM** إلى `true`، فإن الدالة تتضمن [علامة ترتيب البايت (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

هذه الدالة مخصصة للاستخدام مع باركودات 2D فقط (مثل Aztec، QR، DataMatrix، PDF417، MaxiCode، DotCode، HanXin، RectMicroQR، إلخ). تتيح ترميز يدوي لنص Unicode باستخدام ترميزات وطنية أو خاصة؛ ومع ذلك، تُعتبر هذه الطريقة قديمة في التطبيقات الحديثة. لحالات الاستخدام الحديثة، يُنصح باستخدام ترميز [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) لبيانات Unicode.

استخدام هذه الدالة مع باركودات 1D، أو باركودات متوافقة مع GS1 (بما في ذلك 2D)، أو باركودات HIBC (بما في ذلك 2D) غير مدعوم من قبل معايير الباركود المقابلة وقد يؤدي إلى نتائج غير متوقعة.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| codeText | String | سلسلة CodeText |
| الترميز | الترميز | الترميز المطبق |
| insertBOM | Boolean | يشير إلى ما إذا كان يجب إدراج علامة ترتيب البايت (BOM) عندما يدعم الترميز المحدد ذلك (مثال: UTF-8، UTF-16، UTF-32). إذا تم تعيينه إلى `true`، يتم إضافة الـ BOM؛ إذا تم تعيينه إلى `false`، يتم حذف الـ BOM حتى إذا كان الترميز يستخدمه عادةً. |

## أمثلة

يوضح هذا المثال كيفية استخدام `SetCodeText` مع أو بدون علامة BOM لباركودات 2D.

```csharp
[C#]
//ترميز codetext باستخدام UTF-8 مع BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//ترميز codetext باستخدام UTF-8 بدون BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### انظر أيضًا

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


