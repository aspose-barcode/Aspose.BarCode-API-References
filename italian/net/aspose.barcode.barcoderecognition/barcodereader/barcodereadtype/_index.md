---
title: "BarCodeReader.BarCodeReadType"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Proprietà BarCodeReader. Ottiene o imposta il tipo di decodifica del codice a barre usato per il riconoscimento. Deve essere impostato prima di chiamare ReadBarCodes"
type: docs
weight: 30
url: /it/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

Ottiene o imposta il tipo di decodifica del codice a barre usato per il riconoscimento. Deve essere impostato prima di chiamare [`ReadBarCodes`](../readbarcodes/).

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Vedi anche

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


