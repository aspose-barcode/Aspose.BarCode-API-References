---
title: Class MaxiCodeCodetextMode3
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.MaxiCodeCodetextMode3 class. Class for encoding and decoding the text embedded in the MaxiCode code for modes 3
type: docs
weight: 600
url: /net/aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
## MaxiCodeCodetextMode3 class

Class for encoding and decoding the text embedded in the MaxiCode code for modes 3.

```csharp
public class MaxiCodeCodetextMode3 : MaxiCodeStructuredCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [MaxiCodeCodetextMode3](maxicodecodetextmode3/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CountryCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/countrycode/) { get; set; } | Identifies 3 digit country code. |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Gets or sets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | Gets or sets a MaxiCode encode mode. Default value: Auto. |
| [PostalCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/postalcode/) { get; set; } | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [SecondMessage](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/secondmessage/) { get; set; } | Identifies second message of the barcode. |
| [ServiceCategory](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/servicecategory/) { get; set; } | Identifies 3 digit service category. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | Returns a value indicating whether this instance is equal to a specified [`MaxiCodeStructuredCodetext`](../maxicodestructuredcodetext/) value. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Gets barcode type. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | Constructs codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | Returns the hash code for this instance. |
| override [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetextmode3/getmode/)() | Gets MaxiCode mode. |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | Initializes instance from constructed codetext. |

## Examples

This sample shows how to encode and decode MaxiCode codetext for mode 3.

```csharp
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

### See Also

* class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


