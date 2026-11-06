---
title: "فئة Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام فئة Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder في C++."
type: docs
weight: 1900
url: /ar/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | يضيف codetext مع وضع الترميز المحدد إلى عناصر codetext الموسعة |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | يضيف نصًا مشفرًا مع معرف القناة الموسعة |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | يضيف codetext مع معرف القناة الموسعة مع وضع الترميز المحدد |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | يضيف نصًا مشفرًا عاديًا إلى عناصر النص المشفر الموسعة |
| virtual [Clear](../extcodetextbuilder/clear/)() | يمسح عناصر النص المشفر الموسعة |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | ينشئ نصًا مشفرًا موسعًا من قائمة النص المشفر الموسعة. |
## ملاحظات


مولد codetext الموسع لباركودات DataMatrix ثنائية الأبعاد لوضع ExtendedCodetext في EncodeMode


```cpp
[C#]
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
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## انظر أيضًا

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
