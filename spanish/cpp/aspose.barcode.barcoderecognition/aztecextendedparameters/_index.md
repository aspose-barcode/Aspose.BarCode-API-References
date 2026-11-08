---
title: "Clase Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters. Almacena datos especiales del código de barras Aztec reconocido en C++."
type: docs
weight: 300
url: /es/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Almacena datos especiales del código de barras Aztec reconocido

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** si todos los parámetros tienen solo valores predeterminados |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Indica si el código se utiliza para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Obtiene el ID del código de barras en modo de anexado estructurado Aztec. El ID comienza en 1 y debe ser menor o igual al número de códigos de barras. El valor predeterminado es 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Obtiene la cantidad de códigos de barras en modo de anexado estructurado Aztec. El valor predeterminado es 0. La cantidad debe ser un valor de 1 a 26. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Obtiene el ID de archivo del modo de anexado estructurado Aztec. El valor predeterminado es una cadena vacía. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [AztecExtendedParameters](./). |
## Observaciones


Este ejemplo muestra cómo obtener los valores sin procesar de Aztec.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## Ver también

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
