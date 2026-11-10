---
title: "BarCodeReader.ReadBarCodes"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader मेथड। इमेज से BarCodeResults पढ़ता है"
type: docs
weight: 110
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader.ReadBarCodes method

इमेज से [`BarCodeResult`](../../barcoderesult/)s पढ़ता है।

```csharp
public BarCodeResult[] ReadBarCodes()
```

### वापसी मान

इमेज पर मान्यता प्राप्त [`BarCodeResult`](../../barcoderesult/)s का एरे रिटर्न करता है। यदि कुछ भी मान्यता नहीं प्राप्त होता, तो शून्य एरे रिटर्न किया जाता है।

## उदाहरण

यह उदाहरण दिखाता है कि BarCodeReader के साथ बारकोड कैसे पढ़ें।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
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

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### और देखें

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


