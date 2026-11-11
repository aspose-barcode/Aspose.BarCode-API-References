---
title: "Enumeración BarCodeConfidence"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enumeración Aspose.BarCode.BarCodeRecognition.BarCodeConfidence. Contiene el nivel de confianza del reconocimiento."
type: docs
weight: 50
url: /es/net/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enumeration

Contiene el nivel de confianza del reconocimiento

```csharp
public enum BarCodeConfidence
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Confianza del reconocimiento del código de barras donde el texto del código no se reconoció correctamente o el código de barras se detectó como posible falsificación. |
| Moderate | `80` | Confianza del reconocimiento del código de barras (principalmente códigos de barras 1D) con suma de verificación débil o incluso sin ella. Podría contener algunas misreconocimientos en el texto del código o incluso reconocimientos falsos si es bajo. |
| Strong | `100` | Confianza del reconocimiento que se confirmó con códigos BCH como Reed–Solomon. No debe haber errores en el texto del código leído ni reconocimientos falsos. |

## Ejemplos

Este ejemplo muestra cómo BarCodeConfidence cambia, dependiendo del tipo de código de barras.

```csharp
[C#]
//Confianza moderada
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}

//Confianza alta
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


