---
title: "BarcodeSettings.StripFNC"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BarcodeSettings. Elimina los caracteres FNC1, FNC2 y FNC3 del texto del código. El valor predeterminado es false"
type: docs
weight: 60
url: /es/net/aspose.barcode.barcoderecognition/barcodesettings/stripfnc/
---
## BarcodeSettings.StripFNC property

Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. Valor predeterminado es false.

```csharp
public bool StripFNC { get; set; }
```

### Property Value

Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. Valor predeterminado es false.

## Ejemplos

Este ejemplo muestra cómo eliminar los caracteres FNC

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC deshabilitado
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC habilitado
    reader.BarcodeSettings.StripFNC = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC disabled
    reader.BarcodeSettings.StripFNC = False
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC enabled
    reader.BarcodeSettings.StripFNC = True
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ver también

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


