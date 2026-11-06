---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext فئة"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext فئة. الفئة الأساسية للترميز وفك الترميز للنص المضمن في رمز MaxiCode للوضعي 2 و 3 في C++."
type: docs
weight: 2200
url: /ar/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأوضاع 2 و3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [MaxiCodeStructuredCodetext](./) محددة. |
| [get_CountryCode](./get_countrycode/)() const | يحدد رمز الدولة المكوّن من 3 أرقام. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |
| [get_PostalCode](./get_postalcode/)() const | يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3. |
| [get_SecondMessage](./get_secondmessage/)() const | يحدد الرسالة الثانية للباركود. |
| [get_ServiceCategory](./get_servicecategory/)() const | يحدد فئة الخدمة المكوّنة من 3 أرقام. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | ينشئ نص الترميز |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | يحصل على وضع MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | يحدد رمز الدولة المكوّن من 3 أرقام. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | يضبط وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |
| [set_PostalCode](./set_postalcode/)(System::String) | يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | يحدد الرسالة الثانية للباركود. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | يحدد فئة الخدمة المكوّنة من 3 أرقام. |
## ملاحظات


هذا المثال يوضح كيفية فك ترميز نص MaxiCode الخام إلى مثيل [MaxiCodeStructuredCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

## انظر أيضًا

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
