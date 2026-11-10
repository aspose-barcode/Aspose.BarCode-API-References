---
title: "BarCodeReader.BarCodeReadType"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader प्रॉपर्टी। पहचान के लिए उपयोग किए जाने वाले बारकोड डिकोड प्रकार को प्राप्त करता है या सेट करता है। ReadBarCodes को कॉल करने से पहले इसे सेट करना आवश्यक है।"
type: docs
weight: 30
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

पहचान के लिए उपयोग किए जाने वाले बारकोड डिकोड प्रकार को प्राप्त करता है या सेट करता है। [`ReadBarCodes`](../readbarcodes/) को कॉल करने से पहले इसे सेट करना आवश्यक है।

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

### और देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


