---
title: "BarcodeSettings.DetectEncoding"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarcodeSettings प्रॉपर्टी। वह फ़्लैग जो इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए बाध्य करता है। डिफ़ॉल्ट मान true है।"
type: docs
weight: 40
url: /hi/net/aspose.barcode.barcoderecognition/barcodesettings/detectencoding/
---
## BarcodeSettings.DetectEncoding property

वह फ़्लैग जो इंजन को Unicode कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करता है। डिफ़ॉल्ट मान true है।

```csharp
public bool DetectEncoding { get; set; }
```

### Property Value

वह फ़्लैग जो इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए बाध्य करता है।

## उदाहरण

यह उदाहरण दिखाता है कि यदि DetectEncoding सक्षम है तो टेक्स्ट एन्कोडिंग को रीयल‑टाइम में कैसे पता किया जाए।

```csharp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //यूनिकोड कोडसेट्स के लिए एन्कोडिंग का पता लगाना सक्षम है।
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //एन्कोडिंग का पता लगाना अक्षम है।
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### और देखें

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


