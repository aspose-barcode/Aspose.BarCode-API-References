---
title: "BarCodeReader.BarCodeReadType"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BarCodeReader. Obtiene o establece el tipo de decodificación de código de barras usado para el reconocimiento. Debe establecerse antes de llamar a ReadBarCodes."
type: docs
weight: 30
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

Obtiene o establece el tipo de decodificación de código de barras usado para el reconocimiento. Debe establecerse antes de llamar a [`ReadBarCodes`](../readbarcodes/).

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

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

### Ver también

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


