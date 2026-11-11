---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método BarCodeReader. Establece una matriz de tipo SingleDecodeType para el reconocimiento. Debe llamarse antes del método ReadBarCodes"
type: docs
weight: 130
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

Establece una matriz de tipo [`SingleDecodeType`](../../singledecodetype/) para el reconocimiento. Debe llamarse antes del método ReadBarCodes().

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | La matriz de tipo [`SingleDecodeType`](../../singledecodetype/) a leer. |

## Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

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

### Ver también

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


