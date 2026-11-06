---
title: "فئة Aspose::BarCode::Generation::DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام فئة Aspose::BarCode::Generation::DotCodeExtCodetextBuilder في C++."
type: docs
weight: 2100
url: /ar/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | يضيف نصًا مشفرًا مع معرف القناة الموسعة |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | يضيف معرف تنسيق FNC1 إلى عناصر النص الموسع |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | يضيف تهيئة قارئ FNC3 إلى عناصر النص الموسع |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | يضيف فاصل رمز FNC3 إلى عناصر النص الموسع |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | يضيف نصًا مشفرًا عاديًا إلى عناصر النص المشفر الموسعة |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | يضيف وضع الإلحاق المُنظم إلى عناصر النص الموسع |
| virtual [Clear](../extcodetextbuilder/clear/)() | يمسح عناصر النص المشفر الموسعة |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | ينشئ نصًا مشفرًا موسعًا من قائمة النص المشفر الموسعة. |
## ملاحظات


مولد النص الموسع لباركودات DotCode ثنائية الأبعاد لوضع ExtendedCodetext في DotCodeEncodeMode


```cpp
[C#]
//وضع النص المشفر الموسع
//إنشاء نص مشفر
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//توليد نص مشفر
string codetext = textBuilder.GetExtendedCodetext();

//توليد
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## انظر أيضًا

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
