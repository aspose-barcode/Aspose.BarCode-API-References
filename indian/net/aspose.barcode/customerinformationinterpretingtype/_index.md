---
title: "एनम CustomerInformationInterpretingType"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.CustomerInformationInterpretingType एनम। ऑस्ट्रेलियन पोस्ट बारकोड के लिए ग्राहक जानकारी के CTable, NTable या Other व्याख्या प्रकार को परिभाषित करता है"
type: docs
weight: 910
url: /hi/net/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enumeration

ऑस्ट्रेलियनपोस्ट बारकोड के लिए ग्राहक जानकारी के व्याख्या प्रकार (CTable, NTable या अन्य) को परिभाषित करता है।

```csharp
public enum CustomerInformationInterpretingType
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| CTable | `0` | ग्राहक जानकारी की व्याख्या के लिए CTable का उपयोग करें। A..Z, a..z, 1..9, स्पेस और # चिह्न की अनुमति देता है। |
| NTable | `1` | ग्राहक जानकारी की व्याख्या के लिए NTable का उपयोग करें। अंकों की अनुमति देता है। |
| Other | `2` | ग्राहक जानकारी की व्याख्या न करें। केवल 0, 1, 2 या 3 प्रतीक की अनुमति देता है। |

## उदाहरण

ये नमूने दिखाते हैं कि ऑस्ट्रेलिया पोस्ट बारकोड कैसे उत्पन्न और पहचानें

```csharp
[C#]
//यह नमूना दिखाता है कि CTable व्याख्या प्रकार के साथ ऑस्ट्रेलिया पोस्ट बारकोड कैसे उत्पन्न और पहचानें।
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
//यह नमूना दिखाता है कि ग्राहक व्याख्या प्रकार के बिना ऑस्ट्रेलिया पोस्ट बारकोड कैसे उत्पन्न और पहचानें।
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

### और देखें

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


