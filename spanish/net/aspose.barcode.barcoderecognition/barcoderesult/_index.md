---
title: BarCodeResult
second_title: Referencia de API de Aspose.BarCode para .NET
description: Almacena datos de códigos de barras reconocidos comoSingleDecodeType./singledecodetype escribeString texto en código BarCodeRegionParameters./barcoderegionparameters región y otros parámetros
type: docs
weight: 90
url: /es/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Almacena datos de códigos de barras reconocidos como[`SingleDecodeType`](../singledecodetype) escribe,String texto en código, [`BarCodeRegionParameters`](../barcoderegionparameters) región y otros parámetros

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarCodeResult](barcoderesult)(BarCodeResult) | Crea una copia de la[`BarCodeResult`](../barcoderesult) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes) { get; } | Obtiene los bytes del código codificado |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext) { get; } | Obtiene el texto del código |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype) { get; } | Obtiene el tipo de código de barras |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename) { get; } | Obtiene el nombre del tipo de código de barras |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence) { get; } | Obtiene el nivel de confianza de reconocimiento del código de barras reconocido |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended) { get; } | Obtiene parámetros extendidos de código de barras reconocido |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality) { get; } | Obtiene la calidad de lectura. Funciona para códigos de barras 1D y postales. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region) { get; } | Obtiene la región del código de barras |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone)() | Crea una copia de[`BarCodeResult`](../barcoderesult) clase. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals)(BarCodeResult) | Devuelve un valor que indica si esta instancia es igual a una especificada[`BarCodeResult`](../barcoderesult) valor. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals_1)(object) | Devuelve un valor que indica si esta instancia es igual a una especificada[`BarCodeResult`](../barcoderesult) valor. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext)(Encoding) | Obtiene el texto del código con codificación. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode)() | Devuelve el código hash de esta instancia. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring)() | Devuelve una representación de cadena legible por humanos de este[`BarCodeResult`](../barcoderesult) . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality) | Devuelve un valor que indica si el primer[`BarCodeResult`](../barcoderesult) el valor es igual al segundo. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality) | Devuelve un valor que indica si la primera[`BarCodeResult`](../barcoderesult) el valor es diferente del segundo. |

### Ejemplos

Este ejemplo muestra cómo obtener BarCodeResult.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### Ver también

* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
