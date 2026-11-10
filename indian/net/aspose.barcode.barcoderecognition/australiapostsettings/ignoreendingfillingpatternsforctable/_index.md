---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "AustraliaPostSettings प्रॉपर्टी। वह फ़्लैग जो AustraliaPost डिकोडर को CTable विधि के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भरने पैटर्न को अनदेखा करने के लिए मजबूर करता है। CTable एन्कोडिंग विधि में एन्कोडिंग टेबल में कोई अंतर नहीं है और भरने पैटर्न की क्रमांक 333 को अक्षर z के रूप में डिकोड किया जाता है।"
type: docs
weight: 30
url: /hi/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

फ़्लैग जो AustraliaPost डिकोडर को डिकोडिंग के दौरान कस्टमर इन्फॉर्मेशन फ़ील्ड में अंतिम भरने पैटर्न को CTable विधि के रूप में अनदेखा करने के लिए मजबूर करता है। CTable एन्कोडिंग विधि में एन्कोडिंग टेबल में कोई गैप नहीं होते और भरने पैटर्न की श्रृंखला \"333\" को अक्षर \"z\" के रूप में डिकोड किया जाता है।

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

फ़्लैग जो CTable विधि डिकोडिंग के दौरान AustraliaPost डिकोडर को अंतिम भरने पैटर्न को अनदेखा करने के लिए मजबूर करता है

## उदाहरण

यह उदाहरण दर्शाता है कि कैसे CTable इंटरप्रेटिंग टाइप के साथ Australia Post बारकोड उत्पन्न और पहचानें तथा भरने पैटर्न को अनदेखा करें।

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

### और देखें

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


