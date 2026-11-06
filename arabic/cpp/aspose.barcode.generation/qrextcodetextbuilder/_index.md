---
title: "فئة Aspose::BarCode::Generation::QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام فئة Aspose::BarCode::Generation::QrExtCodetextBuilder في C++."
type: docs
weight: 4300
url: /ar/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | يضيف نص الكود مع وضع ضغط QR المحدد إلى عناصر نص الكود الموسعة. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | يضيف نصًا مشفرًا مع معرف القناة الموسعة |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | يضبط FNC1 في الموضع الأول. إذا تم ضبط وضع FNC1 آخر مسبقًا، يتم استبداله. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | يضيف فاصل المجموعة (GS - '\\u001D') إلى عناصر النص المشفر الموسع |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | يضبط FNC1 في الموضع الثاني. إذا تم ضبط وضع FNC1 آخر مسبقًا، يتم استبداله. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | يضيف نصًا مشفرًا عاديًا إلى عناصر النص المشفر الموسعة |
| [Clear](./clear/)() override | يمسح عناصر النص المشفر الموسعة |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | ينشئ نصًا مشفرًا موسعًا من قائمة النص المشفر الموسعة. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## ملاحظات


مولد النص المشفر الموسع لباركودات QR ثنائية الأبعاد لوضع ExtendedCodetext في EncodeMode

استخدم خاصية TwoDDisplayText لكائن [BarcodeGenerator](../barcodegenerator/) لتعيين النص الظاهر وإزالة الأحرف الإدارية.

تُظهر هذه العينة كيفية استخدام الموضع الأول لـ FNC1 في الوضع الموسع.
```cpp
[C#]
//إنشاء نص مشفر
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//توليد نص مشفر
string codetext = TextBuilder.GetExtendedCodetext();

//توليد
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


تُظهر هذه العينة كيفية استخدام الموضع الثاني لـ FNC1 في الوضع الموسع.
```cpp
[C#]
//إنشاء نص مشفر
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//توليد نص مشفر
string codetext = TextBuilder.GetExtendedCodetext();

//توليد
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


تُظهر هذه العينة كيفية استخدام وضع ECI متعدد في الوضع الموسع.
```cpp
[C#]
//إنشاء نص مشفر
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//توليد نص مشفر
string codetext = TextBuilder.GetExtendedCodetext();

//توليد
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## انظر أيضًا

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
