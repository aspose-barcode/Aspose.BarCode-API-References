---
title: "Clase Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters. Almacena datos especiales del código de barras Code128 reconocido en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Almacena datos especiales del código de barras Code128 reconocido

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | Obtiene la matriz [Code128DataPortion](../code128dataportion/) del código de barras Code128 reconocido |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** si todos los parámetros tienen solo valores predeterminados |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [Code128ExtendedParameters](./). |
## Observaciones


Representa la región del código de barras reconocido y el ángulo del código de barras

Este ejemplo muestra cómo obtener los valores sin procesar de code128
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

## Ver también

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
