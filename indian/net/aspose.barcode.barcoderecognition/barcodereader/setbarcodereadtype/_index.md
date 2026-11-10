---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader मेथड। मान्यता के लिए SingleDecodeType प्रकार का एरे सेट करता है। ReadBarCodes मेथड से पहले इसे कॉल करना आवश्यक है"
type: docs
weight: 130
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

[`SingleDecodeType`](../../singledecodetype/) प्रकार का एरे मान्यता के लिए सेट करता है। ReadBarCodes() मेथड से पहले इसे कॉल करना आवश्यक है।

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | पढ़ने के लिए [`SingleDecodeType`](../../singledecodetype/) प्रकार का एरे। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### और देखें

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


