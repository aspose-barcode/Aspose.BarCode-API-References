---
title: "فئة Aspose::BarCode::Generation::BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::BarcodeGenerator. BarcodeGenerator لتوليد صور الباركود الخلفية في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | إنشاء نسخة من [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | إنشاء نسخة من [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | نظّف أي موارد قيد الاستخدام. |
| [ExportToXml](./exporttoxml/)(System::String) | يصدّر خصائص [BarCode](../../aspose.barcode/) إلى ملف XML المحدد |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | يصدّر خصائص [BarCode](../../aspose.barcode/) إلى تدفق XML المحدد |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | توليد صورة الباركود وفق الإعدادات الحالية. |
| [get_BarcodeType](./get_barcodetype/)() | نوع ترميز الباركود. |
| [get_CodeText](./get_codetext/)() | النص المراد ترميزه. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) المعلمات. |
| static [ImportFromXml](./importfromxml/)(System::String) | يستورد خصائص [BarCode](../../aspose.barcode/) من ملف XML المحدد ويُنشئ مثيلًا لـ [BarcodeGenerator](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | يستورد خصائص [BarCode](../../aspose.barcode/) من تدفق XML المحدد ويُنشئ مثيلًا لـ [BarcodeGenerator](./). |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | احفظ صورة الباركود إلى تدفق بتنسيق محدد. |
| [Save](./save/)(System::String, BarCodeImageFormat) | احفظ صورة الباركود إلى ملف محدد بتنسيق محدد. |
| [Save](./save/)(System::String) | احفظ صورة الباركود إلى ملف محدد. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | نوع ترميز الباركود. |
| [set_CodeText](./set_codetext/)(System::String) | النص المراد ترميزه. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | عيّن نص الرمز كسلسلة من البايتات. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## ملاحظات


الترميزات المدعومة: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

يعرض هذا المثال كيفية إنشاء وحفظ صورة باركود.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
