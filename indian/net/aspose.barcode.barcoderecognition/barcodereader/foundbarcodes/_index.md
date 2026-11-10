---
title: "BarCodeReader.FoundBarCodes"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader प्रॉपर्टी। मान्यता प्राप्त BarCodeResults एरे प्राप्त करता है"
type: docs
weight: 50
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/
---
## BarCodeReader.FoundBarCodes property

मान्यता प्राप्त [`BarCodeResult`](../../barcoderesult/)s एरे प्राप्त करता है

```csharp
public BarCodeResult[] FoundBarCodes { get; }
```

### Property Value

मान्यता प्राप्त [`BarCodeResult`](../../barcoderesult/)s एरे

## उदाहरण

यह उदाहरण दिखाता है कि BarCodeReader के साथ बारकोड कैसे पढ़ें।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

### और देखें

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


