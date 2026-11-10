---
title: "BarCodeReader.BarCodeReadType"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeReader-Eigenschaft. Gibt den Barcode-Dekodierungstyp zurück oder legt ihn fest, der für die Erkennung verwendet wird. Muss gesetzt werden, bevor ReadBarCodes aufgerufen wird."
type: docs
weight: 30
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

Gibt den Barcode-Dekodierungstyp zurück oder legt ihn fest, der für die Erkennung verwendet wird. Muss gesetzt werden, bevor [`ReadBarCodes`](../readbarcodes/) aufgerufen wird.

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


