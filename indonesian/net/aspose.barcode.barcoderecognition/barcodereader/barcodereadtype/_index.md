---
title: "BarCodeReader.BarCodeReadType"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Properti BarCodeReader. Mendapatkan atau mengatur jenis dekode barcode yang digunakan untuk pengenalan. Harus diatur sebelum memanggil ReadBarCodes"
type: docs
weight: 30
url: /id/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

Mendapatkan atau mengatur jenis dekode barcode yang digunakan untuk pengenalan. Harus diatur sebelum memanggil [`ReadBarCodes`](../readbarcodes/).

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

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

### Lihat Juga

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


