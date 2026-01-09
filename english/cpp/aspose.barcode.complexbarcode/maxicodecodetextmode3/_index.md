---
title: Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 class
linktitle: MaxiCodeCodetextMode3
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 class. Class for encoding and decoding the text embedded in the MaxiCode code for modes 3 in C++.'
type: docs
weight: 1600
url: /cpp/aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
## MaxiCodeCodetextMode3 class


Class for encoding and decoding the text embedded in the MaxiCode code for modes 3.

```cpp
class MaxiCodeCodetextMode3 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/) value. |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() | Identifies 3 digit country code. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() | Gets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Gets a MaxiCode encode mode. Default value: Auto. |
| [get_MaxiCodeEncodeMode](../maxicodecodetext/get_maxicodeencodemode/)() | Gets a MaxiCode encode mode. Default value: Auto. |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | Identifies second message of the barcode. |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() | Identifies 3 digit service category. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Gets barcode type. |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | Constructs codetext |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | Returns the hash code for this instance. |
| [GetMode](./getmode/)() const override | Gets MaxiCode mode. |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | Initializes instance from constructed codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | Identifies 3 digit country code. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Aspose::BarCode::Generation::ECIEncodings) | Sets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Aspose::BarCode::Generation::MaxiCodeEncodeMode) | Sets a MaxiCode encode mode. Default value: Auto. |
| [set_MaxiCodeEncodeMode](../maxicodecodetext/set_maxicodeencodemode/)(Aspose::BarCode::Generation::MaxiCodeEncodeMode) | Sets a MaxiCode encode mode. Default value: Auto. |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifies second message of the barcode. |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | Identifies 3 digit service category. |
## Remarks


This sample shows how to encode and decode MaxiCode codetext for mode 3. 
```cpp
[C#]
//Mode 3 with standard second message
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 3 with structured second message
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
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
//Decoding raw codetext with standard second message
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode3){
            MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
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
//Decoding raw codetext with structured second message
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode3){
            MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
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

## See Also

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
