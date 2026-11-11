---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad AustraliaPostSettings. La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el Campo de Información del Cliente durante la decodificación con el método CTable. El método de codificación CTable no tiene huecos en la tabla de codificación y la secuencia 333 de patrones de relleno se decodifica como la letra z"
type: docs
weight: 30
url: /es/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el Campo de Información del Cliente durante la decodificación como método CTable. El método de codificación CTable no tiene huecos en la tabla de codificación y la secuencia "333" de patrones de relleno se decodifica como la letra "z".

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno durante la decodificación con el método CTable

## Ejemplos

Este ejemplo muestra cómo generar y reconocer códigos de barras Australia Post con el Tipo de Interpretación CTable y omitiendo los patrones de relleno.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

### Ver también

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


