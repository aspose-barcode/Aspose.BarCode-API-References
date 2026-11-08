---
title: "enum"
linktitle: "CustomerInformationInterpretingType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Define el tipo de interpretación (CTable, NTable o Other) de la información del cliente para AustralianPost BarCode en C++."
type: docs
weight: 700
url: /es/cpp/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enum


Define el tipo de interpretación (CTable, NTable o Other) de la información del cliente para AustralianPost [BarCode](../).

```cpp
enum class CustomerInformationInterpretingType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| CTTable | 0 | Utilice CTable para interpretar la información del cliente. Permite A..Z, a..z, 1..9, espacio y el signo #. |
| NTable | 1 | Utilice NTable para interpretar la información del cliente. Permite dígitos. |
| Other | 2 | No interprete la información del cliente. Permite solo el símbolo 0, 1, 2 o 3. |

## Observaciones


Estos ejemplos muestran cómo generar y reconocer códigos de barras de Australia Post
```cpp
    [C#]
//Este ejemplo muestra cómo generar y reconocer códigos de barras de Australia Post con el tipo de interpretación CTable.
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
//Esta muestra muestra cómo generar y reconocer códigos de barras de Australia Post sin el Customer Interpreting Type.
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## Ver también

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
