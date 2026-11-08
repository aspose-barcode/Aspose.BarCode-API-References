---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters clase"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters clase. Almacena datos especiales del código de barras DotCode reconocido en C++."
type: docs
weight: 2000
url: /es/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


Almacena datos especiales del código de barras DotCode reconocido

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** si todos los parámetros tienen solo valores predeterminados |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Indica si el código se utiliza para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Obtiene el ID del código de barras en modo de anexado estructurado DotCode. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Obtiene el recuento de códigos de barras en modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor entre 1 y 35. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ToString](./tostring/)() const override | Devuelve una representación en cadena legible por humanos de este [DotCodeExtendedParameters](./). |
## Observaciones


Este ejemplo muestra cómo obtener los valores sin procesar de DotCode
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## Ver también

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
