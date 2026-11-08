---
title: "Clase Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters. Almacena datos especiales del código de barras DataMatrix reconocido en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Almacena datos especiales del código de barras [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) reconocido

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** si todos los parámetros tienen solo valores predeterminados |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Indica si el código se utiliza para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Obtiene el ID del código de barras [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) en modo Structured Append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Obtiene el recuento de códigos de barras [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) en modo Structured Append. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Obtiene el ID del código de barras [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) en modo Structured Append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [DataMatrixExtendedParameters](./). |
## Observaciones


Este ejemplo muestra cómo obtener los valores sin procesar de [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## Ver también

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
