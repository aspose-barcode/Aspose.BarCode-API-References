---
title: "BarCodeReader.ReadBarCodes"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método BarCodeReader. Lee BarCodeResults de la imagen"
type: docs
weight: 110
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader.ReadBarCodes method

Lee [`BarCodeResult`](../../barcoderesult/)s de la imagen.

```csharp
public BarCodeResult[] ReadBarCodes()
```

### Valor de retorno

Devuelve una matriz de [`BarCodeResult`](../../barcoderesult/)s reconocidos en la imagen. Si no se reconoce nada, se devuelve una matriz vacía.

## Ejemplos

Este ejemplo muestra cómo leer códigos de barras con BarCodeReader.

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

### Ver también

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


