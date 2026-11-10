---
title: "BarCodeReader.Timeout"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader प्रॉपर्टी। मान्यता प्रक्रिया का टाइमआउट मिलीसेकंड में प्राप्त या सेट करता है"
type: docs
weight: 80
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

मिलीसेकंड में मान्यता प्रक्रिया का टाइमआउट प्राप्त करता है या सेट करता है।

```csharp
public int Timeout { get; set; }
```

### Property Value

समय समाप्ति।

## उदाहरण

यह उदाहरण दिखाता है कि बड़े चित्रों पर टाइमआउट के साथ पहचान के अटकने से कैसे बचा जाए

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


