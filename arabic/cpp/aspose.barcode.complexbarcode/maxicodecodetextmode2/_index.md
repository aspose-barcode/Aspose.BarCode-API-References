---
title: "فئة Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2. فئة لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأوضاع 2 في C++."
type: docs
weight: 1700
url: /ar/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
## MaxiCodeCodetextMode2 class


فئة لتشفير وفك تشفير النص المضمن في رمز MaxiCode للطور 2.

```cpp
class MaxiCodeCodetextMode2 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/) محددة. |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | يحدد رمز الدولة المكوّن من 3 أرقام. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3. |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | يحدد الرسالة الثانية للباركود. |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | يحدد فئة الخدمة المكوّنة من 3 أرقام. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | ينشئ نص الترميز |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [GetMode](./getmode/)() const override | يحصل على وضع MaxiCode. |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | يحدد رمز الدولة المكوّن من 3 أرقام. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | يضبط وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3. |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | يحدد الرسالة الثانية للباركود. |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | يحدد فئة الخدمة المكوّنة من 3 أرقام. |
## ملاحظات


يعرض هذا المثال كيفية تشفير وفك تشفير نص MaxiCode للوضع 2.
```cpp
[C#]
//الوضع 2 مع الرسالة الثانية القياسية
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//الوضع 2 مع الرسالة الثانية المنظمة
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//فك ترميز النص الخام مع الرسالة الثانية القياسية
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandardSecondMessage){
                MaxiCodeStandardSecondMessage secondMessage = (MaxiCodeStandardSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
//فك ترميز النص الخام مع الرسالة الثانية المهيكلة
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

## انظر أيضًا

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
