---
title: ReadBarCodes
second_title: Aspose.BarCode for .NET API Referansı
description: Okuma sayısıBarCodeResultaspose.barcode.barcoderecognition/barcoderesult görüntüden s.
type: docs
weight: 100
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader.ReadBarCodes method

Okuma sayısı[`BarCodeResult`](../../barcoderesult) görüntüden s.

```csharp
public BarCodeResult[] ReadBarCodes()
```

### Geri dönüş değeri

Tanınan diziyi döndürür[`BarCodeResult`](../../barcoderesult)görüntü üzerinde s. Hiçbir şey tanınmazsa, sıfır dizi döndürülür.

### Örnekler

Bu örnek, BarCodeReader ile barkodların nasıl okunacağını gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca bakınız

* class [BarCodeResult](../../barcoderesult)
* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->