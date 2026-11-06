---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext فئة"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext فئة. فئة لتشفير وفك تشفير نص كود MaxiCode للأوضاع 4 و 5 و 6 في C++."
type: docs
weight: 2000
url: /ar/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


فئة لتشفير وفك تشفير نص رمز MaxiCode للأوضاع 4 و5 و6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يرجع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [MaxiCodeStandardCodetext](./) المحددة. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |
| [get_Message](./get_message/)() const | يحصل على الرسالة. |
| [get_Mode](./get_mode/)() | يحصل على وضع MaxiCode. يمكن استخدام نص الكود القياسي فقط مع الأوضاع 4 و 5 و 6. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | ينشئ نص الترميز |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [GetMode](./getmode/)() const override | يحصل على وضع MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | يضبط وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |
| [set_Message](./set_message/)(System::String) | يضبط الرسالة. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | يضبط وضع MaxiCode. يمكن استخدام نص الكود القياسي فقط مع الأوضاع 4 و 5 و 6. |
## ملاحظات


//الوضع 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //الوضع 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //الوضع 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## انظر أيضًا

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
