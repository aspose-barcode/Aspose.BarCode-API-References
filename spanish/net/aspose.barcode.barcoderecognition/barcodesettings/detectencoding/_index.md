---
title: "BarcodeSettings.DetectEncoding"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BarcodeSettings. El indicador que obliga al motor a detectar la codificación del texto del código para juegos de caracteres Unicode. El valor predeterminado es true"
type: docs
weight: 40
url: /es/net/aspose.barcode.barcoderecognition/barcodesettings/detectencoding/
---
## BarcodeSettings.DetectEncoding property

La bandera que obliga al motor a detectar la codificación del texto del código para juegos de caracteres Unicode. Valor predeterminado es true.

```csharp
public bool DetectEncoding { get; set; }
```

### Property Value

El indicador que obliga al motor a detectar la codificación del texto del código para juegos de caracteres Unicode

## Ejemplos

Este ejemplo muestra cómo detectar la codificación del texto sobre la marcha si DetectEncoding está habilitado

```csharp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //la detección de codificación para juegos de caracteres Unicode está habilitada
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //la detección de codificación está deshabilitada
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


