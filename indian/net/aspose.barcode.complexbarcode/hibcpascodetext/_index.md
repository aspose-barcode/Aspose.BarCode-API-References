---
title: "क्लास HIBCPASCodetext"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.HIBCPASCodetext क्लास। HIBC PAS कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने की क्लास"
type: docs
weight: 600
url: /hi/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

HIBC PAS कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | बारकोड प्रकार प्राप्त करता या सेट करता है। HIBC PAS कोडटेक्स्ट को HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS और HIBCQRPAS एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39PAS। |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | डेटा स्थान की पहचान करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | नया रिकॉर्ड जोड़ता है |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | नया रिकॉर्ड जोड़ता है |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | रिकॉर्ड सूची साफ़ करता है |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `HIBCPASCodetext` मान के बराबर है या नहीं। |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | बारकोड प्रकार को प्राप्त करता है। |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | कोडटेक्स्ट बनाता है। |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | रिकॉर्ड सूची प्राप्त करता है |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | निर्मित कोडटेक्स्ट से इंस्टेंस को प्रारंभ करता है। |

## उदाहरण

यह उदाहरण दिखाता है कि HIBCPASCodetext का उपयोग करके HIBC PAS को कैसे एन्कोड और डिकोड किया जाता है।

```csharp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText; 
		HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
		Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

### और देखें

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


