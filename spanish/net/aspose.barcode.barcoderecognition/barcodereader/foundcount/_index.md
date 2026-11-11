---
title: "BarCodeReader.FoundCount"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BarCodeReader. Obtiene el recuento de códigos de barras reconocidos."
type: docs
weight: 60
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Obtiene el recuento de códigos de barras reconocidos

```csharp
public int FoundCount { get; }
```

### Property Value

El recuento de códigos de barras reconocidos.

## Ejemplos

Este ejemplo muestra cómo leer códigos de barras con BarCodeReader.

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

### Ver también

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


