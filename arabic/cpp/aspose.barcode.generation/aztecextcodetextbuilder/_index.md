---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder class"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام فئة Aspose::BarCode::Generation::AztecExtCodetextBuilder في C++."
type: docs
weight: 200
url: /ar/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | يضيف نصًا مشفرًا مع معرف القناة الموسعة |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | يضيف نصًا مشفرًا عاديًا إلى عناصر النص المشفر الموسعة |
| virtual [Clear](../extcodetextbuilder/clear/)() | يمسح عناصر النص المشفر الموسعة |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | ينشئ نصًا مشفرًا موسعًا من قائمة النص المشفر الموسعة. |
## ملاحظات


مولد النص المشفر الموسع لباركودات Aztec لوضع ExtendedCodetext في AztecEncodeMode

استخدم خاصية TwoDDisplayText لكائن [BarcodeGenerator](../barcodegenerator/) لتعيين النص الظاهر وإزالة الأحرف الإدارية.

يعرض هذا المثال كيفية استخدام [AztecExtCodetextBuilder](./) في الوضع الموسع.
```cpp
[C#]
//إنشاء نص مشفر
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//توليد نص مشفر
string codetext = textBuilder.GetExtendedCodetext();

//توليد
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## انظر أيضًا

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
