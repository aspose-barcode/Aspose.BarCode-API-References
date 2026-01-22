---
title: Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext class
linktitle: MaxiCodeStructuredCodetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext class. Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3 in C++.'
type: docs
weight: 2100
url: /cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [MaxiCodeStructuredCodetext](./) value. |
| [get_CountryCode](./get_countrycode/)() | Identifies 3 digit country code. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() | Gets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Gets a MaxiCode encode mode. Default value: Auto. |
| [get_MaxiCodeEncodeMode](../maxicodecodetext/get_maxicodeencodemode/)() | Gets a MaxiCode encode mode. Default value: Auto. |
| [get_PostalCode](./get_postalcode/)() | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [get_SecondMessage](./get_secondmessage/)() const | Identifies second message of the barcode. |
| [get_ServiceCategory](./get_servicecategory/)() | Identifies 3 digit service category. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Gets barcode type. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Constructs codetext |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | Gets MaxiCode mode. |
| [InitFromString](./initfromstring/)(System::String) override | Initializes instance from constructed codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | Identifies 3 digit country code. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Aspose::BarCode::Generation::ECIEncodings) | Sets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Aspose::BarCode::Generation::MaxiCodeEncodeMode) | Sets a MaxiCode encode mode. Default value: Auto. |
| [set_MaxiCodeEncodeMode](../maxicodecodetext/set_maxicodeencodemode/)(Aspose::BarCode::Generation::MaxiCodeEncodeMode) | Sets a MaxiCode encode mode. Default value: Auto. |
| [set_PostalCode](./set_postalcode/)(System::String) | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Identifies second message of the barcode. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | Identifies 3 digit service category. |
## Remarks


This sample shows how to decode raw MaxiCode codetext to [MaxiCodeStructuredCodetext](./) instance. 
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

## See Also

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
