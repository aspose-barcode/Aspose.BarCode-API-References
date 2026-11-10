---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeReader-Methode. Setzt das SingleDecodeType-Typ-Array für die Erkennung. Muss vor der ReadBarCodes-Methode aufgerufen werden."
type: docs
weight: 130
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

Setzt das [`SingleDecodeType`](../../singledecodetype/) Typ-Array für die Erkennung. Muss vor der ReadBarCodes()-Methode aufgerufen werden.

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | Das [`SingleDecodeType`](../../singledecodetype/) Typ-Array zum Lesen. |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


