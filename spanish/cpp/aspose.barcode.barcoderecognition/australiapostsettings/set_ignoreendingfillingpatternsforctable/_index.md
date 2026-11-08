---
title: "método"
linktitle: "set_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el Campo de Información del Cliente durante la decodificación como método CTable. El método de codificación CTable no tiene huecos en la tabla de codificación y la secuencia \"333\" de patrones de relleno se decodifica como la letra \"z\" en C++."
type: docs
weight: 400
url: /es/cpp/aspose.barcode.barcoderecognition/australiapostsettings/set_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable method


La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el Campo de Información del Cliente durante la decodificación como método CTable. El método de codificación CTable no tiene huecos en la tabla de codificación y la secuencia "333" de patrones de relleno se decodifica como la letra "z".

```cpp
void Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable(bool value)
```

## Observaciones


La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno durante la decodificación con el método CTable

Este ejemplo muestra cómo generar y reconocer códigos de barras Australia Post con el Tipo de Interpretación CTable e ignorando los patrones de relleno.
```cpp
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

## Ver también

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
